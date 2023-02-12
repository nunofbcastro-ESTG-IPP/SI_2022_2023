<h1 align="center">Practical Work on Sistemas de Informação (Information systems)</h1>

<p>
  <img src="http://img.shields.io/static/v1?style=for-the-badge&label=School%20year&message=2022/2023&color=sucess"/>
  <img src="http://img.shields.io/static/v1?style=for-the-badge&label=Discipline&message=SI&color=sucess"/>
  <a href="https://github.com/nunofbcastro-ESTG-IPP/SI_2022_2023/tree/main/Enunciado" target="_blank">
    <img src="https://img.shields.io/badge/-Utterance-grey?style=for-the-badge"/>
  </a>
  <a href="https://github.com/nunofbcastro-ESTG-IPP/SI_2022_2023/tree/main/Relatorio" target="_blank">
    <img src="https://img.shields.io/badge/-Report-grey?style=for-the-badge"/>
  </a>
</p>

---

<h2>Languages</h2>
<p align="left"> 
  <img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=Next.js&amp;color=000000&amp;logo=Next.js&amp;logoColor=FFFFFF&amp;label=" alt="Next.js">
<img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=PostgreSQL&amp;color=4169E1&amp;logo=PostgreSQL&amp;logoColor=FFFFFF&amp;label=" alt="PostgreSQL">
<img src="https://img.shields.io/static/v1?style=for-the-badge&amp;message=Docker&amp;color=2496ED&amp;logo=Docker&amp;logoColor=FFFFFF&amp;label=" alt="Docker">
</p>

---

<h2>How to run</h2>

<h3>Database</h3>

```
cd postgres
docker compose up
```

<h3>Project</h3>

1. In the file si_grupo_g/.env
  - Change the value of the API_NIF variable to the key from the website https://www.nif.pt.
  - Change the value of the EMAIL and EMAIL_PASS variables to your Gmail credentials.
  - Change the value of the TOCOnline_CLIENT_ID and TOCOnline_CLIENT_SECRET variables to the values from the https://www.toconline.pt API.
  - Change the value of the TOCOnline_KEY_BASE64 variable to the base64-encrypted value of TOCOnline_CLIENT_ID:TOCOnline_CLIENT_SECRET.
```
API_NIF="key"
...
EMAIL=email
EMAIL_PASS=password
...
TOCOnline_CLIENT_ID="key"
TOCOnline_CLIENT_SECRET="key"
TOCOnline_KEY_BASE64="key"
...
NEXT_PUBLIC_GOOGLE_ANALYTICS="key"
```
2. Run
```
yarn install
yarn run dev
```
3. Endpoint [http://localhost:3000](http://localhost:3000)

---

<h2>Authors</h2>

<h3>
  Nuno Castro
  <a href="https://github.com/nunofbcastro?tab=followers">
    <img src="https://img.shields.io/github/followers/nunofbcastro.svg?style=social&label=Follow" />
  </a>
</h3>

<h3>
  Bruno Ferreira
  <a href="https://github.com/brunoferreira0106?tab=followers">
    <img src="https://img.shields.io/github/followers/brunoferreira0106.svg?style=social&label=Follow" />
  </a>
</h3>

<h3>
  Gonçalo Oliveira
  <a href="https://github.com/oliveira1712?tab=followers">
    <img src="https://img.shields.io/github/followers/oliveira1712.svg?style=social&label=Follow" />
  </a>
</h3>

<h3>
  Jorge Correia
  <a href="https://github.com/JorgeMFC?tab=followers">
    <img src="https://img.shields.io/github/followers/JorgeMFC.svg?style=social&label=Follow" />
  </a>
</h3>

<h3>
  Luís Sousa
  <a href="https://github.com/luisousa14?tab=followers">
    <img src="https://img.shields.io/github/followers/luisousa14.svg?style=social&label=Follow" />
  </a>
</h3>
