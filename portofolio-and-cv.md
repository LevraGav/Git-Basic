# Jawaban No 2 Technical Assessment Skilvul - Git & Github

1. membuat sebuah folder kosong dengan namamu sendiri <br>
![image](https://user-images.githubusercontent.com/72689610/134144173-de7d3325-dd71-421a-82db-f7a9e89b1d61.png) <br>
```mkdir arvel-gavrilla-raissananda```

2. membuat sebuah file dengan nama ```README.md```, isi file tersebut dengan kalimat ```"Halo perkenalkan aku halaman utama"``` <br>
![image](https://user-images.githubusercontent.com/72689610/134156783-1037e164-8551-4435-879f-751bdfc690ff.png) <br>
![image](https://user-images.githubusercontent.com/72689610/134156841-b1b85957-96b5-45a3-a07e-be6eae55b5cf.png) <br>
```touch README.md```

3. insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan ```commit``` dengan pesan ```"Inisialisasi Git Repository"``` <br>
![image](https://user-images.githubusercontent.com/72689610/134157344-b1f1cdcb-3fda-422f-a5cf-bda742b23817.png) <br>
```git init``` <br>
```git add README.md``` <br>
```git commit -m "Inisialisasi Git Repository"``` <br>

4. buat ```branch``` baru dengan nama ```cv```, hal ini berguna agar histori kita tidak tercampur <br>
![image](https://user-images.githubusercontent.com/72689610/134157715-22f4a140-ec27-4fc8-97ce-0b21e5a7f424.png) <br>
```git branch cv```

5. pindah ```branch``` kedalam ```cv```, kemudian buat file dengan nama ```cv.txt``` dan isi file tersebut dengan kalimat: ```"Ini adalah file CV"``` <br>
![image](https://user-images.githubusercontent.com/72689610/134158255-e06c27df-fbd1-47b0-ad4b-1f14d3dbafaa.png) <br>
![image](https://user-images.githubusercontent.com/72689610/134158655-dccb0e45-7079-44c0-ad77-3b9d58475e4b.png) <br>
```git checkout cv``` <br>
```touch cv.txt```

6. kemudian dokumentasikan menggunakan commit dengan pesan : ```"Inisialisasi CV"``` <br>
![image](https://user-images.githubusercontent.com/72689610/134158939-06dd9112-d660-477d-8d1e-9ffc140e419e.png) <br>
```git add cv.txt``` <br>
```git commit -m "Inisialisasi CV"```

7. tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan ```commit``` <br>
![image](https://user-images.githubusercontent.com/72689610/134159343-5d7ab62e-12d1-49b1-84b6-5dc5a1d02810.png) <br>
![image](https://user-images.githubusercontent.com/72689610/134159395-d98fcf01-1074-428f-9680-0f7e87d47de4.png) <br>
```git add cv.txt``` <br>
```git commit -m "adding Gojek to CV"``` <br> <br>
![image](https://user-images.githubusercontent.com/72689610/134159538-4a77acd3-33cd-4e23-acf9-9fdc70d160d5.png) <br>
![image](https://user-images.githubusercontent.com/72689610/134159669-51ee83cd-ba47-4324-a4b4-a328fc95a793.png) <br>
```git add cv.txt``` <br>
```git commit -m "adding Shopee to CV"``` <br> <br>
![image](https://user-images.githubusercontent.com/72689610/134159744-7d0d4676-3a7a-4932-b017-05a52df724cc.png) <br>
![image](https://user-images.githubusercontent.com/72689610/134159823-8f30696c-cc15-4397-93e3-a93eb4447cfc.png) <br>
```git add cv.txt``` <br>
```git commit -m "adding Tokopedia to CV"```

8. kembali ke branch ```master``` <br>
![image](https://user-images.githubusercontent.com/72689610/134160004-06bfca29-2ffa-4ec6-884a-3beba18a6014.png) <br>
```git checkout master```

9. ubah file ```README.md``` menjadi <br>
```
Halo perkenalkan aku halaman utama

Ini adalah update pertama pada branch master
``` 
jangan lupa untuk mendokumentasikannya menggunakan ```commit``` dengan pesan ```"update master pertama"``` <br>
![image](https://user-images.githubusercontent.com/72689610/134160313-b28491b0-dc60-45bc-80d6-83430ebd1d73.png) <br>
![image](https://user-images.githubusercontent.com/72689610/134160721-c11bb583-dbef-4070-8478-862a1b7a5e96.png) <br>
```git add README.md``` <br>
```git commit -m "update master pertama"```

10. gabungkan ```branch cv``` kedalam ```branch master``` menggunakan perintah ```git merge``` <br>
![image](https://user-images.githubusercontent.com/72689610/134161171-f5ff41c6-761a-4f5c-ad36-a87736bc0094.png) <br>
```git merge cv```

11. unggah Git Repository tersebut kedalam GitHub <br>
![image](https://user-images.githubusercontent.com/72689610/134161370-a740367c-e8ef-4235-ab43-d973e25b4d41.png) <br>
```git push --set-upstream origin master```

# Note
```git log --graph``` <br>
![image](https://user-images.githubusercontent.com/72689610/134161889-173778dc-7d7b-4cdf-990d-69218460531b.png)




















