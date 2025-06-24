
              </div>
              <a 
                href="https://youtube.com/@radouane779?si=aHjjwwYHYBZ9-_yi" 
                target="_blank" 
                rel="noopener noreferrer"
                className="w-8 h-8 bg-red-600 hover:bg-red-700 rounded-full flex items-center justify-center transition-colors"
              >
                <Youtube className="w-4 h-4 text-white" />
              </a>
            </div>
          </div>

          <div className="text-center">
            <h4 className="text-lg font-semibold text-palestine-400 mb-4">روابط مهمة</h4>
            <ul className="space-y-2">
              <li>
                <a href="#home" className="text-palestine-200 hover:text-palestine-400 transition-colors">
                  الرئيسية
                </a>
              </li>
              <li>
                <a href="#features" className="text-palestine-200 hover:text-palestine-400 transition-colors">
                  الميزات
                </a>
              </li>
              <li>
                <a href="#uploader" className="text-palestine-200 hover:text-palestine-400 transition-colors">
                  ترجمة الفيديو
                </a>
              </li>
              <li>
                <a href="#about" className="text-palestine-200 hover:text-palestine-400 transition-colors">
                  عن الموقع
                </a>
              </li>
            </ul>
          </div>

          <div className="text-center md:text-left">
            <h4 className="text-lg font-semibold text-palestine-400 mb-4">دعم فلسطين</h4>
            <div className="space-y-3">
              <p className="text-palestine-200 text-sm">
                هذا الموقع مجاني ومفتوح المصدر لدعم القضية الفلسطينية
              </p>
              <div className="palestine-flag-animation h-8 rounded-md"></div>
              <p className="text-palestine-300 text-xs">
                "فلسطين حرة من النهر إلى البحر"
              </p>
              <a 
                href="https://youtube.com/@radouane779?si=aHjjwwYHYBZ9-_yi" 
                target="_blank" 
                rel="noopener noreferrer"
                className="inline-flex items-center text-palestine-400 hover:text-red-400 transition-colors text-sm"
              >
                <Youtube className="w-4 h-4 ml-2" />
                قناة اليوتيوب
              </a>
            </div>
          </div>
        </div>

        <div className="border-t border-palestine-600 pt-8">
          <div className="flex flex-col md:flex-row justify-between items-center">
            <div className="text-palestine-300 text-sm mb-4 md:mb-0">
              © 2024 فلسطين فيديو سكرايب - جميع الحقوق محفوظة لخدمة القضية الفلسطينية
            </div>
            <div className="flex items-center space-x-4 space-x-reverse text-palestine-300 text-sm">
              <span>صنع بـ</span>
              <Heart className="w-4 h-4 text-red-500" />
              <span>لفلسطين</span>
              <span>🇵🇸</span>
            </div>
          </div>
        </div>
      </div>
    </footer>
  );
};

export default Footer;
