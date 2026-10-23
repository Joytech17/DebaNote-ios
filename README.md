# DebaNote для iPhone (Capacitor 8)
1. Створіть окремий публічний репозиторій на GitHub (наприклад, debanote-ios) і завантажте всі файли з цієї папки (Add file -> Upload files).
2. Файл .github/workflows/build-ios.yml створіть вручну (Add file -> Create new file) і вставте вміст build-ios.yml.
3. Actions -> "Build iOS (unsigned IPA)" -> Run workflow. Через 10-15 хвилин завантажте артефакт debanote-ios-unsigned.
4. Усередині DebaNote-unsigned.ipa. Установіть його через Sideloadly (Windows/Mac) із безкоштовним Apple ID.
