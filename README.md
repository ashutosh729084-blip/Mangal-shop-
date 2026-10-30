# Mangal Shop — Android starter

यह एक शुरुआती demo storefront है, पूरा Amazon/Flipkart-जैसा production marketplace नहीं। इसमें sample products, category filters और demo cart हैं। कोई असली checkout/payment, user account, vendor/admin backend, database, delivery tracking या location sharing नहीं है।

## GitHub से APK बनाना (मोबाइल से)
1. ZIP को extract करें।
2. GitHub में अपनी `Mangal-shop` repository खोलें।
3. **Add file → Upload files** चुनें। ZIP को सीधे upload न करें; ZIP के अंदर की सभी files/folders upload करें। `.github/workflows/build-apk.yml` भी शामिल होना चाहिए।
4. नीचे **Commit changes** दबाएँ।
5. **Actions** टैब खोलें और `Build Mangal Shop Android APK` workflow का run देखें।
6. अगर run हरा (success) हो जाए, उस run को खोलें और **Artifacts** में `Mangal-Shop-Android-APK` डाउनलोड करें। ZIP artifact खोलकर `app-debug.apk` निकालें।

APK build तभी सफल माना जाएगा जब GitHub Actions run सफल हो और artifact दिखाई दे।
