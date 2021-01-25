# Belajar Rust

### Dasar
* [Mengapa Rust](source/docs/a1.why_rust.md)
* [Instalasi](source/docs/a2.installation.md)
* [Hello World](source/docs/a3.hello_world.md)
* [Cargo,crates and struktur project dasar](source/docs/a4.cargo,crates_and_basic_project_structure.md)
* [Komentar dan dokumentasi kode](source/docs/a5.comments_and_documenting_the_code.md)
* [Variabel, konstanta, and statis](source/docs/a6.variable_bindings,constants_and_statics.md)
* [Fungsi](source/docs/a7.functions.md)
* [Tipe data primitiv](source/docs/a8.primitive_data_types.md)
* [Operator](source/docs/a9.operators.md)
* [Pengontrol bersyarat](source/docs/a10.control_flows.md)

### Lebih Jauh Mengenai Dasar Rust
* [Vektor](source/docs/b1.vectors.md)
* [Structs](source/docs/b2.structs.md)
* [Enums](source/docs/b3.enums.md)
* [Generik](source/docs/b4.generics.md)
* [Impls and traits](source/docs/b5.impls_and_traits.md)

### Bagian yang Sulit
* [Ownership](source/docs/c1.ownership.md)
* [Borrowing](source/docs/c2.borrowing.md)
* [Lifetimes](source/docs/c3.lifetimes.md)
    
### Mari kita mulai
* [Code organization](source/docs/d1.code_organization.md)
* [Functions](source/docs/d2.functions.md)
* [Modules](source/docs/d3.modules.md)
* [Crates](source/docs/d4.crates.md)
* [Workspaces](source/docs/d5.workspaces.md)
* [use](source/docs/d6.use.md)
* [std, primitives and preludes](source/docs/d7.std_primitives_and_preludes.md)

### Penanganan Eror
* [Smart Compiler](source/docs/e1.smart_compiler.md)
* [Panicking](source/docs/e2.panicking.md)
* [Option and Result](source/docs/e3.option_and_result.md)
* [Unwrap and Expect](source/docs/e4.unwrap_and_expect.md)
* [Error and None Propagation](source/docs/e5.error_and_none_propagation.md)
* [Combinators](source/docs/e6.combinators.md)
* [Custom Error Types](source/docs/e7.custom_error_types.md)

---
* Situs : http://learning-rust.github.io
* Medium: https://medium.com/learning-rust

> 🐣 Ini adalah sebuah dokumentasi dari seorang Web Developer **Sri Lankan** 🇱🇰 yang tinggal di **Vietnam** 🇻🇳. Jadi, dia ini bukan seorang penutur asli bahasa Inggris, dia ini hanya seorang yang sedang belajar Rust. Bila kamu menemukan kesalahan atau sesuatu yang perlu diubah, dan juga bahkan kesalahan pengejaan atau tatabahasa, aku sangat mengapresiasi bila kamu bisa membuat *pull request*. Terima kasih.

---

# learning-rust.github.io(sumber)

Situs ini dibangun dengan [Hexo](https://hexo.io/) framework blog Nodejs. Kamu bisa lihat hasil di repo [learning-rust/learning-rust.github.io](https://github.com/learning-rust/learning-rust.github.io).

## Permulaan

Instal tool yang dibutuhkan

``` bash
$ git clone git@github.com:learning-rust/site.git
$ cd site
$ npm install
$ npm install hexo-cli -g
```

Generate:

``` bash
$ hexo generate
```

Jalankan server:

``` bash
$ hexo server
```
