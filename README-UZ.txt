SPEAKQUEST AI — iPhone PWA prototipi

Bu ZIP ichidagi index.html — Safari orqali ishlatish uchun veb-prototip. O‘z ichida 4 ta vaziyat, chat UI, ovoz chiqarib o‘qish, ayrim brauzerlarda mikrofon orqali matnga aylantirish, XP va localStorage progress bor. AI backend ulanmaguncha haqiqiy generativ AI emas; oddiy qoidaviy feedback beradi.

iPhone'da faqat telefon bilan:
1) ZIPni Files ichiga yuklab olib ochish mumkin, lekin HTML faylni shunchaki Files'dan ochish PWA o‘rnatish uchun yetarli emas.
2) Fayllarni HTTPS hostingga joylash kerak (masalan GitHub Pages). Buning uchun GitHub akkaunti va Safari'da fayl upload qilish mumkin.
3) Hosted HTTPS URL'ni Safari'da och.
4) Safari Share → Add to Home Screen → Add.
5) AI chat uchun backend host qilish va API key server env vars keessa saqlash kerak. API key'i index.html içine yozma.

Mikrofon speech-to-text iOS Safari'da versiyaga qarab farq qiladi; ishlamasa iPhone klaviaturasidagi dictation tugmasidan foydalan. Text-to-speech Safari speechSynthesis'ni ishlatadi.
