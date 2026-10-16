# SEVA Gym Management System - GitHub Pages Deployment Guide
(सेव्हा जिम मॅनेजमेंट सिस्टीम - गिटहब पेजेस मार्गदर्शक)

प्रकल्प: T.Y.B.Sc. Computer Application (Science)
कॉलेज: S.M.B.S.T. College of Arts, Science and Commerce, Sangamner
विद्यापीठ: Savitribai Phule Pune University
विद्यार्थी: Mr. Nannar Digambar Janku, Mr. Inamdar Nadeem Arif
मार्गदर्शक: Prof. Gaikwad S.B.

---

## या ZIP मधील फाइल्स:
1.  - वेबसाइटचे मुख्य पान (Main HTML entry point with relative asset paths)
2.  - JavaScript bundle आणि CSS stylesheets
3.  - सर्व जिम फोटो, ट्रेनर फोटो आणि इमेजेस
4.  - हे मार्गदर्शक

---

## GitHub Pages वर पब्लिश करण्याच्या 4 सोप्या पायऱ्या (Steps to Deploy):

### पायरी 1: ZIP अनझिप करा
हा  फोल्डर तुमच्या कॉम्प्युटरवर Right-click करून **Extract All** (अनझिप) करा.

### पायरी 2: GitHub वर Repository बनवा
1. https://github.com वर जा आणि लॉगिन करा.
2. हिरव्या **New Repository** बटणावर क्लिक करा.
3. Repository name द्या: 
4. **Public** पर्याय निवडा (हे अत्यंत महत्त्वाचे आहे).
5. **Create repository** वर क्लिक करा.

### पायरी 3: फाइल्स अपलोड करा
1. 'uploading an existing file' या लिंकवर क्लिक करा.
2. अनझिप केलेल्या फोल्डरमधील सर्व फाइल्स (index.html, assets फोल्डर, src फोल्डर) ड्रॅग आणि ड्रॉप करून अपलोड करा.
3. खाली हिरव्या **Commit changes** बटणावर क्लिक करा.

### पायरी 4: GitHub Pages चालू करा
1. Repository च्या वरच्या मेनूमधील **Settings** वर क्लिक करा.
2. डाव्या बाजूच्या मेनूमधील **Pages** वर क्लिक करा.
3. **Build and deployment** अंतर्गत:
   - Source: **Deploy from a branch** निवडा.
   - Branch: **main** (किंवा master) आणि फोल्डर **/ (root)** निवडा.
4. **Save** बटणावर क्लिक करा.

🎉 1-2 मिनिटांत तुमची वेबसाइट खालील लिंकवर इंटरनेटवर लाईव्ह होईल:
https://<तुमचे-GitHub-Username>.github.io/seva-gym/
