# Starlette kullanmak için yapılcaklar
Bash kullanmamız lazım çünkü source cmde'de veya powershell'de yok.(Önerim Git Bash)


Taşınabilir olsun diye  'python -m venv env' komutunu kullanıyoruz.

'source env/Scripts/activate' komutunu kullanarak virtual env'i aktif ediyoruz.

'pip install starlette uvicorn' komutunu çalıştırarak kütüphanemizi yüklüyoruz.(kütüphaneleri yükledikten sonra)

'pip freeze > requirements.txt' Bir projeyi başkasıyla paylaşıyorsanız veya kopyalıyorsanız projenin gerektirdiği dış paketleri belirtmeniz gerekir.Bu kod ise bunu sağlar.

'uvicorn main:app --reload' kodu çalıştırıyoruz.(Uvicorn, Python için bir ASGI web sunucusu uygulamasıdır.) 
