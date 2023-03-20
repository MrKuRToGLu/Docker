1) projenin olduğu dizinde publish oluşturulur

2) Sulution'a sağ click yapılıp Ducker support seçeneği ile docker file eklenir.

3) proje dizininde command prompt(cmd) ekranı açılır

4) docker build -t imageName . (imaj oluşturur)

5) docker images  (imaj listeler)

6) docker create --name containerName ImageName (konteyner oluşturur)

7) docker  ps -a (konteynerları listeler)

7) docker stop containerName (çalışancontainer durdurur)

8) docker rm containerName (konteyner siler)

9) docker run -p localPort:dockerPort --name ContainerName ImageName (konteyner oluşutur ve yayınlar...)