# Writing-Week-5
## React.js
- React : sebuah library untuk membuat tampilan website
- React JS dibuat oleh Tim Engineer Facebook
- keuntungan/kelebihan dari react : Lebih proses cepetnya, misalkan : bikin navbar cukup sekali aja, tidak perlu meng-copas pada codingan tampilan yang lain hanya cukup dipanggil saja navbarnya
- Banyak aplikasi yang dibuat dengan menggunakan react, contohnya fb, ig, uber, twitter
- Java Script hanya bisa berjalan di web browser
- Jadi di dalam browser ada mesin JS yang berjalan didalam web browser, dan NodeJS dapat berjalan diluar browser
- NodeJS adalah aplikasi untuk menajalankan react.js
- Framework java script selain react JS, ada : vue, angular, svelte
### cara mendownload reactJS
1. download NodeJS
2. install nodeJS
3. jika NodeJS sudah terinstall, selanjutnya buat folder baru, beri nama folder
4. klik kanan, pilih git bash
5. ketik "npx create-react-app (nama folder)"
6. maka selanjutnya akan ada proses download
7. tunggu sampai proses download selesai
8. proses download selesai, ditandai dengan tulisan "Happy Hacking!"
### cara menggunakan ReactJS
- buka vs code
- lalu buka terminal, ketik npm start
- buka yang file src
- lalu buka App.js
- kita ngoding di dalam App.js, di dalam function App
- function App () hanya bisa menampung satu element
 ```js
 //index.js
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);

// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
reportWebVitals();


 //App.js
 import './App.css';
 
 function App(){
  return(
    <h1>Syifa></h1>   //output : Syifa
  )
}

export default App;
 ```

- penulisan function di react harus pakai huruf besar diawal. 
```js
function App()
```
- harus ada return
```js
function App(){
  return()
}
```
- hanya boleh ada 1 parent utama <div></div> atau pake tag kosong
```js
function App(){
  return(
  <>
    <h1>Syifa></h1>
  </>
  )
}
```
- Jika ingin pakai pake boostrap, bisa download cdn atau download di npm, lalu pasang di html


ydi react 'class' tidak ada, adanya className

statw adalah sebuah object untuk menyimpan data di react

props digunajan untuk komunikasi dari components parent dan child
ngirim sebuah parameter di function
data ditampung si state, dikirim melalu props

props dipasang di function
const Memberinfo = (props)
clg(prosp)

custom data.
masukin ke app -> {} data baru

useState untuk menyimpan data yg sifatnya berubah2
