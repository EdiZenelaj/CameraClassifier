Camera Classifier App
Një aplikacion i thjeshtë me Tkinter, OpenCV dhe Scikit-learn që përdor kamerën për të klasifikuar imazhet midis dy klasave të ndryshme.

📦 Kërkesat
Python 3.8+

Paketat:

opencv-python

Pillow

scikit-learn

tk

Për të instaluar paketat:

bash
Copy
Edit
pip install opencv-python Pillow scikit-learn
🚀 Si ta nisësh
Sigurohu që ke kamerën e kompjuterit aktive.

Hap terminalin.

Shko në dosjen e projektit dhe nis aplikacionin:

bash
Copy
Edit
python main.py
⚙️ Si funksionon
Kur hapet aplikacioni, kërkon të shkruash emrat e dy klasave që do të përdorësh.

Përdor butonat për të:

Ruajtur foto për secilën klasë (Save for Class),

Trajnuar modelin (Train Model),

Bërë parashikime (Predict),

Aktivizuar parashikim automatik (Auto Prediction),

Fshirë të dhënat (Reset).

📸 Funksionaliteti
Kamera hapet live dhe shfaq videon në dritare.

Foto të ruajtura janë të vogla (150x112 px) për trajnim të shpejtë.

Modeli i klasifikimit është LinearSVC nga scikit-learn.

❗ Shënime të rëndësishme
Para se të përdorësh Predict, sigurohu që ke ruajtur disa foto për çdo klasë dhe ke shtypur Train Model.

Nëse modeli nuk është trajnuar dhe provon të parashikosh, aplikacioni jep një mesazh pa u ndalur me gabim.

📁 Struktura e skedarëve
css
Copy
Edit
.
├── app.py
├── camera.py
├── model.py
├── main.py
└── README.md
