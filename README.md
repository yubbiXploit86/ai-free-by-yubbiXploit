# 🚀 AI FREE — by **yubbiXploit**

Terminal AI untuk Termux — cepat, sederhana, dan personal.  
Proyek ini memakai **OpenAI API** jadi kamu perlu API key sendiri untuk menjalankan.

---

## ⚡ Fitur
- Banner ASCII yang bisa dikustom (`ascii.txt`)  
- API key terpisah dan aman (`apikey.txt`) — **JANGAN** commit file ini ke GitHub  
- Mode chat interaktif (Bahasa Indonesia)  
- Perintah ringkas: `ai`, `ai --set-key`, `ai --edit-ascii`

---

## 📦 Struktur proyek
---

## 🔑 Dapatkan OpenAI API Key
INSTALL SINGKAT 
# setelah clone/download
chmod +x ai
# optional: supaya bisa panggil 'ai' dari mana saja
mkdir -p ~/bin
cp ai ~/bin/
1. Buka: https://platform.openai.com/account/api-keys  
2. Klik **Create new secret key** → salin key  
3. Simpan key lokal:
   ```bash
   ai --set-key
   nano ~/ai-free-by-yubbiXploit/apikey.txt
# paste sk-... lalu simpan
ai --set-key
ai
ai --edit-ascii
---

# B. Upload ke GitHub via web (paling mudah)
1. Buka: **https://github.com/new**  
2. Repository name: **`ai-free-by-yubbiXploit`**  
3. Description (opsional): `AI Termux assistant — by yubbiXploit`  
4. Visibility: Public atau Private  
5. Jangan centang *Initialize with README*  
6. Klik **Create repository**

7. Di repo → klik **Add file → Upload files**  
8. Upload file: `ai`, `ascii.txt`, `.gitignore`, `README.md` (**jangan** upload `apikey.txt`)  
9. Commit message: `Initial commit — ai-free-by-yubbiXploit` → klik **Commit changes**

Selesai — repo sudah online.

---

# C. Jalankan di perangkatmu (setelah download/clone)
1. Download ZIP dari repo atau `git clone https://github.com/<username>/ai-free-by-yubbiXploit.git`  
2. Buat file `apikey.txt` di folder project **lokal** (jangan upload):
```bash
mkdir -p ~/ai-free-by-yubbiXploit
nano ~/ai-free-by-yubbiXploit/apikey.txt
# paste sk-... lalu simpan
