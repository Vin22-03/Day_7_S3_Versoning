# AWS S3 Accidental Delete & Recovery (Versioning Demo)

## 📌 Objective
Simulate a real-world AWS S3 incident where a file is accidentally deleted and recovered using S3 **Versioning** and **Delete Markers**.

---

## 🛠 Skills Learned
- Creating an S3 bucket with Versioning enabled
- Uploading and overwriting objects
- Understanding Version IDs and Delete Markers
- Recovering accidentally deleted objects
- AWS Console troubleshooting

---

## 🏗 Steps Performed
1. **Create S3 Bucket**
   - Enabled **Versioning** during creation.
   
2. **Upload File (v1)**
   - Uploaded `notes.txt` with "This is version 1" content.
   
3. **Upload Updated File (v2)**
   - Overwrote `notes.txt` with "This is version 2".
   
4. **Simulate Accidental Delete**
   - Deleted file from **default S3 view** → Created a Delete Marker.
   
5. **Recover File**
   - Removed Delete Marker → Original file instantly restored.

---

## 📷 Screenshots
Screenshots are in the `/screenshots` folder showing each step.

---

## ⚡ How to Try This Yourself
1. Enable S3 Versioning.
2. Upload a file, then upload a modified version of the same file.
3. Delete from default view → Observe Delete Marker in Versions tab.
4. Remove Delete Marker → File restored.

---

## 🏢 Real-World Use Case
If a critical file is mistakenly deleted in production, S3 Versioning ensures quick recovery without downtime.

---

## 📌 Author
Vin — Aspiring Cloud & DevOps Engineer 🚀
