sudo /usr/libexec/PlistBuddy -c "Delete :Kernel:Patch" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch array" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0 dict" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:Count integer 1" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:Find data aGliZXJuYXRlaGlkcmVhZHkAaGliZXJuYXRlY291bnQA" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:Identifier string kernel" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:Limit integer 0" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:Mask data" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:MaxKernel string" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:MinKernel string 20.4.0" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:Replace data aGliZXJuYXRlaGlkcmVhZHkAaHZfdm1tX3ByZXNlbnQA" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:ReplaceMask data" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:0:Skip integer 0" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1 dict" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:Count integer 1" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:Find data Ym9vdCBzZXNzaW9uIFVVSUQAaHZfdm1tX3ByZXNlbnQA" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:Identifier string kernel" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:Limit integer 0" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:Mask data" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:MaxKernel string" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:MinKernel string 22.0.0" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:Replace data Ym9vdCBzZXNzaW9uIFVVSUQAaGliZXJuYXRlY291bnQA" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:ReplaceMask data" /Volumes/EFI/EFI/OC/config.plist
sudo /usr/libexec/PlistBuddy -c "Add :Kernel:Patch:1:Skip integer 0" /Volumes/EFI/EFI/OC/config.plist
