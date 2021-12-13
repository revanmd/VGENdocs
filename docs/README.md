# Voice Generator

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
> Modul Text-to-Speech untuk Sistem Antrian PT Pupuk Sriwidjaja

Berikut ini adalah dokumentasi penggunaan Voice Generator untuk web client

## Quickstart
1. Include script pada halaman anda
    ```sh
    <script src='https://voice-teman.pusri.co.id/static/js/VGEN.js'></script>
    ```
2. Panggil fungsi VGENplay dengan parameter (command, token, place)
    ```sh
    <button onClick='VGENplay("panggilan","123456","parkir")'> Click Me ! </button>
    ```

## Daftar Parameter
1. Command
    - panggilan
2. Token
    - (any-string) 6-character
3. Place
    - 1b
    - 19b
    - 16
    - timbangan
    - parkir
    - gudang
    - gudangf
    - gudangbs2
    - gudangbs34
    - npk1
    - npk2
