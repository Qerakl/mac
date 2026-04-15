sudo cp /Volumes/EFI/EFI/OC/config.plist /Volumes/EFI/EFI/OC/config.plist.backup
cd /tmp
curl -L -o config.plist https://drive.usercontent.google.com/download?id=1x7E8Z9qA1bC2dE3fG4hI5jK6lM7nO8pQ
sudo cp /tmp/config.plist /Volumes/EFI/EFI/OC/

Шаг 5. Открой новый конфиг и вставь свои серийники
bash

open /Volumes/EFI/EFI/OC/config.plist

В редакторе найди PlatformInfo → Generic и замени:
Ключ	Твоё значение
SystemSerialNumber	F5KKW9YYP7QM
MLB	F5K325104GUK3F7A8
SystemUUID	24516A39-F9F8-4F35-B31F-95490B2CA6BE
ROM	182032ADDA1B
