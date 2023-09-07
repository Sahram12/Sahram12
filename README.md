- 👋 Hi, I’m @Sahram12
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Sahram12/Sahram12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->pass
				else:
					pil=input("[?] Ingin menjeda program selama 60 detik (1 menit) [y/n] ")
					if pil.lower() == 'y':
						for x in range(60):
							try:
								print(end=f"\r[!] Jeda {60-(x+1)} detik",flush=True)
								time.sleep(1)
							except: break
						print("\n[OK] Lanjutss")
					elif pil.lower() == 'f':
						henti_tanya=True
					else:
						forcecon+=1
						if forcecon >= 3:
							print(f"[!] {c}tekan F untuk menghentikan pertanyaan{w}")
			elif "challengeID" in r1.text:
				print(f"[+] {c}TARGET{cout} {g}BERHASIL{w}")
			else:
				print(f"[-] {c}TARGET{cout} {r}GAGAL{w}")
			time.sleep(10)
			cout+=1
	print("{end}"+"="*40+"{end}")
except KeyboardInterrupt:
	print("\n%ssampai jumpa gan..."%(c))
