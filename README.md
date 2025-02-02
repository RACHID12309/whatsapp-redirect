<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عمل من المنزل - فرص عمل مرنة للنساء</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 min-h-screen">
    <div class="container mx-auto px-4 py-8 max-w-3xl">
        <!-- Header Section -->
        <header class="text-center mb-12">
            <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">
                ابدئي عملك من المنزل الآن! 
            </h1>
            <p class="text-lg text-gray-600">
                فرصة حقيقية للنساء الراغبات في تحقيق دخل إضافي بدون خبرة مسبقة.<br>
                نوفر دعمًا وتدريبًا مجانيًا لمساعدتك على النجاح!
            </p>
        </header>

        <!-- Benefits Grid -->
        <div class="grid md:grid-cols-2 gap-6 mb-12">
            <div class="bg-white p-6 rounded-xl shadow-sm">
                <h3 class="text-xl font-semibold text-green-600 mb-3">✓ بدون رأس مال</h3>
                <p class="text-gray-600">ابدئي مباشرة دون أي تكاليف مبدئية</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-sm">
                <h3 class="text-xl font-semibold text-green-600 mb-3">✓ مرونة كاملة</h3>
                <p class="text-gray-600">اشتري في الأوقات التي تناسب جدولك</p>
            </div>
        </div>

        <!-- FAQ Section -->
        <div class="bg-white rounded-xl shadow-sm p-6 mb-12">
            <h2 class="text-2xl font-bold text-gray-800 mb-6">الأسئلة الشائعة</h2>
            <div class="space-y-4">
                <details class="border-b pb-4">
                    <summary class="font-semibold text-gray-700 cursor-pointer">كيف يمكنني البدء؟</summary>
                    <p class="mt-2 text-gray-600">انقري على زر "الحصول على التفاصيل" وسنرسل لك كل المعلومات</p>
                </details>
                <details class="border-b pb-4">
                    <summary class="font-semibold text-gray-700 cursor-pointer">هل أحتاج إلى خبرة؟</summary>
                    <p class="mt-2 text-gray-600">لا حاجة لخبرة مسبقة، نوفر تدريبًا مجانيًا</p>
                </details>
            </div>
        </div>

        <!-- Trigger Button -->
        <div class="text-center">
            <button id="detailsButton"
                    class="inline-block bg-blue-600 hover:bg-blue-700 text-white px-12 py-4 rounded-full text-lg font-medium shadow-lg transition-all mb-4">
                الحصول على التفاصيل
            </button>
            
            <p class="text-gray-600 mt-6">
                أو ارسلي رسالة عبر البريد الإلكتروني:<br>
                <a href="mailto:info@example.com" class="text-green-600 hover:underline">info@example.com</a>
            </p>
        </div>

        <!-- WhatsApp Button -->
        <div id="whatsappButton" class="hidden fixed bottom-0 left-0 right-0 bg-white p-4 text-center shadow-lg z-50">
            <a href="https://wa.me/212656674162?text=مرحبًا،%20أريد%20المزيد%20من%20التفاصيل%20عن%20عمل%20المنزل"
               target="_blank"
               class="inline-block bg-[#25D366] text-white px-12 py-4 rounded-full text-lg font-medium w-full">
               تواصلي معنا على واتساب
               <svg class="w-6 h-6 inline-block mr-2" fill="currentColor" viewBox="0 0 24 24">
                   <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
               </svg>
            </a>
        </div>

        <!-- Compliance Footer -->
        <footer class="mt-12 text-center">
            <a href="#privacy-policy" class="text-gray-500 text-sm hover:underline">سياسة الخصوصية</a>
        </footer>
    </div>

    <script>
        document.getElementById('detailsButton').addEventListener('click', function() {
            const whatsappButton = document.getElementById('whatsappButton');
            whatsappButton.style.display = 'block';
            whatsappButton.classList.remove('hidden');
        });
    </script>
</body>
</html>
