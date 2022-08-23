## Install Rupstup

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Mengkonfigurasi PATH variabel lingkungan

Di lingkungan pengembangan Rust, semua alat diinstal ke direktori, dan di sinilah Anda akan menemukan rantai alat Rust, termasuk , , dan . `~/.cargo/bin` `rustc` `cargo` `rustup`

Oleh karena itu, pengembang Rust biasanya menyertakan direktori ini dalam variabel lingkungan mereka . Selama instalasi akan mencoba untuk mengkonfigurasi file . Karena perbedaan antara platform, shell perintah, dan bug di , modifikasi mungkin tidak berlaku hingga konsol dimulai ulang, atau pengguna logout, atau mungkin tidak berhasil sama sekali. `PATH` `rustup` `PATH` `rustup` `PATH`

Jika, setelah instalasi, berjalan `rustc --version` di konsol gagal, ini adalah alasan yang paling mungkin.

## Copot pemasangan Rust

Jika suatu saat Anda ingin menghapus Rust, Anda dapat menjalankan `rustup self uninstall` Kami akan merindukanmu sekalipun!
