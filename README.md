# Debian x86_64 .deb builder for Rust TLS Server
To build rts as deb package simply clone repository and execute:

> dpkg-deb --build rts-x86_64-create-deb
>
> sudo dpkg -i --force-overwrite rts-x86_64-create-deb.deb
>
> rts
