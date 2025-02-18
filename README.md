# ESXi670-202403001-standart-customized
This ISO build was created on last official ESXi 6.7.0 U3 "ESXi670-202403001-standart" with added Realtek RTL 8125 2.5GbE NIC driver - net-r8125-9.011.00-10.

VMware ESXi670-202403001 Release Notes (https://techdocs.broadcom.com/content/dam/broadcom/techdocs/us/en/pdf/vmware/vsphere/vsphere/vSphere-6-7-Release-Notes/esxi670-202403001.pdf):
- Profile Name	ESXi-6.7.0-20240304001-standard
- Build	For build information, see Patches Contained in this Release.
- Vendor	VMware by Broadcom, Inc.
- Release Date	March 05, 2024
- Acceptance Level	PartnerSupported
- Affected Hardware	N/A
- Affected Software	N/A
- Affected VIBs:
    VMware_bootbank_esx-update_6.7.0-3.193.23084122
    VMware_bootbank_esx-base_6.7.0-3.193.23084122
    VMware_bootbank_vsanhealth_6.7.0-3.193.22695748
    VMware_bootbank_vsan_6.7.0-3.193.22695747
    VMW_bootbank_xhci-xhci_1.0-3vmw.670.3.193.23084122
- PRs Fixed	N/A
- Related CVE numbers	CVE-2024-22252, CVE-2024-22253, CVE-2024-22254, CVE-2024-22255

RTL 8125 2.5GBe vibs for use with ESXi 6.7 were sourced from https://github.com/mcr-ksh/r8125-esxi
