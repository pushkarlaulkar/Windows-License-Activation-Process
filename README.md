# Windows-License-Activation-Process
Process of windows license activation

# Windows 2019 Server Standard License Activation

1. ` DISM /online /Set-Edition:ServerStandard /ProductKey:N69G4-B89J2–4G8F4-WWYCC-J464C /AcceptEula `    ##Windows KMS public key
2. ` DISM /online /Set-Edition:ServerStandard /ProductKey:<your-product-key> /AcceptEula ` & then reboot
3. If above doesn’t work then try ` slmgr /ipk <your-product-key> ` & then reboot
4. If this also doesn’t work then try through GUI & then reboot


# Windows 2022 Server Standard License Activation

1. ` DISM /online /Set-Edition:ServerStandard /ProductKey:VDYBN-27WPP-V4HQT-9VMD4-VMK7H /AcceptEula `    ##Windows KMS public key
2. ` DISM /online /Set-Edition:ServerStandard /ProductKey:<your-product-key> /AcceptEula ` & then reboot
3. If above doesn’t work then try ` slmgr /ipk <your-product-key> ` & then reboot
4. If this also doesn’t work then try through GUI & then reboot
