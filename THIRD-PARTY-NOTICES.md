# Third-party notices

The TLS-450PLUS Simulator includes the components below, each under its own
licence. Their licences apply to them; the simulator's own licence (LICENSE)
does not limit the rights they give. The full licence texts are published with
each component (crates.io, or the files named below).

## Shipped files, fonts and data

| Component | Licence | Note |
| --- | --- | --- |
| Droid Sans, Droid Sans Mono | Apache-2.0 | The touchscreen's fonts (Google, Android Open Source Project). Licence text installed as LICENSE-Droid.txt. |
| DejaVu Sans | Bitstream Vera Fonts licence, public domain changes | The help pages' font. Licence text installed as LICENSE-DejaVu.txt. |
| WebView2Loader.dll | Microsoft WebView2 SDK licence (redistributable) | Microsoft's loader for the Edge WebView2 runtime, shipped beside the exe. |
| NSIS | zlib/libpng | The installer is built with the Nullsoft Scriptable Install System. |
| Open-Meteo weather data | CC BY 4.0 | Weather data by Open-Meteo.com, used by the bench's weather feature. |

## Rust crates compiled into the program

| Crate | Version | Licence |
| --- | --- | --- |
| ab_glyph | v0.2.32 | Apache-2.0 |
| ab_glyph_rasterizer | v0.1.10 | Apache-2.0 |
| adler2 | v2.0.1 | 0BSD OR MIT OR Apache-2.0 |
| ahash | v0.8.12 | MIT OR Apache-2.0 |
| arrayref | v0.3.9 | BSD-2-Clause |
| arrayvec | v0.7.8 | MIT OR Apache-2.0 |
| ascii | v1.1.0 | Apache-2.0 OR MIT |
| base64 | v0.22.1 | MIT OR Apache-2.0 |
| bitflags | v2.13.2 | MIT OR Apache-2.0 |
| block-buffer | v0.10.4 | MIT OR Apache-2.0 |
| bytemuck | v1.25.2 | Zlib OR Apache-2.0 OR MIT |
| bytes | v1.12.1 | MIT |
| cfg-if | v1.0.5 | MIT OR Apache-2.0 |
| chunked_transfer | v1.5.0 | MIT OR Apache-2.0 |
| cookie | v0.18.2 | MIT OR Apache-2.0 |
| cpufeatures | v0.2.17 | MIT OR Apache-2.0 |
| crc32fast | v1.5.2 | MIT OR Apache-2.0 |
| crossbeam-channel | v0.5.17 | MIT OR Apache-2.0 |
| crossbeam-utils | v0.8.23 | MIT OR Apache-2.0 |
| crypto-common | v0.1.7 | MIT OR Apache-2.0 |
| deranged | v0.5.9 | MIT OR Apache-2.0 |
| digest | v0.10.7 | MIT OR Apache-2.0 |
| displaydoc | v0.2.7 | MIT OR Apache-2.0 |
| dpi | v0.1.2 | Apache-2.0 AND MIT |
| dunce | v1.0.5 | CC0-1.0 OR MIT-0 OR Apache-2.0 |
| fallible-iterator | v0.3.0 | MIT/Apache-2.0 |
| fallible-streaming-iterator | v0.1.9 | MIT/Apache-2.0 |
| fdeflate | v0.3.7 | MIT OR Apache-2.0 |
| flate2 | v1.1.10 | MIT OR Apache-2.0 |
| form_urlencoded | v1.2.2 | MIT OR Apache-2.0 |
| generic-array | v0.14.7 | MIT |
| getrandom | v0.2.17 | MIT OR Apache-2.0 |
| hashbrown | v0.14.5 | MIT OR Apache-2.0 |
| hashlink | v0.9.1 | MIT OR Apache-2.0 |
| http | v1.5.0 | MIT OR Apache-2.0 |
| httpdate | v1.0.3 | MIT OR Apache-2.0 |
| icu_collections | v2.3.0 | Unicode-3.0 |
| icu_locale_core | v2.3.0 | Unicode-3.0 |
| icu_normalizer | v2.3.0 | Unicode-3.0 |
| icu_normalizer_data | v2.3.0 | Unicode-3.0 |
| icu_properties | v2.3.0 | Unicode-3.0 |
| icu_properties_data | v2.3.0 | Unicode-3.0 |
| icu_provider | v2.3.1 | Unicode-3.0 |
| idna | v1.1.0 | MIT OR Apache-2.0 |
| idna_adapter | v1.2.2 | Apache-2.0 OR MIT |
| itoa | v1.0.18 | MIT OR Apache-2.0 |
| libc | v0.2.191 | MIT OR Apache-2.0 |
| libsqlite3-sys | v0.30.1 | MIT |
| litemap | v0.8.3 | Unicode-3.0 |
| lock_api | v0.4.14 | MIT OR Apache-2.0 |
| log | v0.4.34 | MIT OR Apache-2.0 |
| memchr | v2.8.3 | Unlicense OR MIT |
| miniz_oxide | v0.8.9 | MIT OR Zlib OR Apache-2.0 |
| miniz_oxide | v0.9.1 | MIT OR Zlib OR Apache-2.0 |
| num-conv | v0.2.2 | MIT OR Apache-2.0 |
| once_cell | v1.21.4 | MIT OR Apache-2.0 |
| owned_ttf_parser | v0.25.1 | Apache-2.0 |
| parking_lot | v0.12.5 | MIT OR Apache-2.0 |
| parking_lot_core | v0.9.12 | MIT OR Apache-2.0 |
| percent-encoding | v2.3.2 | MIT OR Apache-2.0 |
| png | v0.18.1 | MIT OR Apache-2.0 |
| potential_utf | v0.1.6 | Unicode-3.0 |
| powerfmt | v0.2.1 | MIT OR Apache-2.0 |
| proc-macro2 | v1.0.107 | MIT OR Apache-2.0 |
| quote | v1.0.47 | MIT OR Apache-2.0 |
| raw-window-handle | v0.6.2 | MIT OR Apache-2.0 OR Zlib |
| ring | v0.17.14 | Apache-2.0 AND ISC |
| rusqlite | v0.32.1 | MIT |
| rustls | v0.23.46 | Apache-2.0 OR ISC OR MIT |
| rustls-pki-types | v1.15.1 | MIT OR Apache-2.0 |
| rustls-webpki | v0.103.16 | ISC |
| scopeguard | v1.2.0 | MIT OR Apache-2.0 |
| serde_core | v1.0.229 | MIT OR Apache-2.0 |
| serde_json | v1.0.151 | MIT OR Apache-2.0 |
| sha2 | v0.10.9 | MIT OR Apache-2.0 |
| simd-adler32 | v0.3.10 | MIT |
| smallvec | v1.16.3 | MIT OR Apache-2.0 |
| stable_deref_trait | v1.2.1 | MIT OR Apache-2.0 |
| strict-num | v0.1.1 | MIT |
| subtle | v2.6.1 | BSD-3-Clause |
| syn | v2.0.119 | MIT OR Apache-2.0 |
| syn | v3.0.6 | MIT OR Apache-2.0 |
| synstructure | v0.14.0 | MIT |
| tao | v0.37.2 | Apache-2.0 |
| thiserror | v2.0.21 | MIT OR Apache-2.0 |
| thiserror-impl | v2.0.21 | MIT OR Apache-2.0 |
| time | v0.3.55 | MIT OR Apache-2.0 |
| time-core | v0.1.9 | MIT OR Apache-2.0 |
| time-macros | v0.2.32 | MIT OR Apache-2.0 |
| tiny-skia | v0.12.0 | BSD-3-Clause |
| tiny-skia-path | v0.12.0 | BSD-3-Clause |
| tiny_http | v0.12.0 | MIT OR Apache-2.0 |
| tinystr | v0.8.4 | Unicode-3.0 |
| ttf-parser | v0.25.1 | MIT OR Apache-2.0 |
| typenum | v1.20.1 | MIT OR Apache-2.0 |
| unicode-ident | v1.0.26 | (MIT OR Apache-2.0) AND Unicode-3.0 |
| unicode-segmentation | v1.13.3 | MIT OR Apache-2.0 |
| untrusted | v0.9.0 | ISC |
| ureq | v2.12.1 | MIT OR Apache-2.0 |
| url | v2.5.8 | MIT OR Apache-2.0 |
| utf8_iter | v1.0.4 | Apache-2.0 OR MIT |
| webpki-roots | v0.26.11 | CDLA-Permissive-2.0 |
| webpki-roots | v1.0.10 | CDLA-Permissive-2.0 |
| webview2-com | v0.39.1 | MIT |
| webview2-com-macros | v0.8.1 | MIT |
| webview2-com-sys | v0.39.1 | MIT |
| windows | v0.62.2 | MIT OR Apache-2.0 |
| windows-collections | v0.3.2 | MIT OR Apache-2.0 |
| windows-core | v0.62.2 | MIT OR Apache-2.0 |
| windows-future | v0.3.2 | MIT OR Apache-2.0 |
| windows-implement | v0.60.2 | MIT OR Apache-2.0 |
| windows-interface | v0.59.3 | MIT OR Apache-2.0 |
| windows-link | v0.2.1 | MIT OR Apache-2.0 |
| windows-numerics | v0.3.1 | MIT OR Apache-2.0 |
| windows-result | v0.4.1 | MIT OR Apache-2.0 |
| windows-strings | v0.5.1 | MIT OR Apache-2.0 |
| windows-threading | v0.2.1 | MIT OR Apache-2.0 |
| windows-version | v0.1.7 | MIT OR Apache-2.0 |
| writeable | v0.6.4 | Unicode-3.0 |
| wry | v0.57.1 | Apache-2.0 OR MIT |
| yoke | v0.8.3 | Unicode-3.0 |
| yoke-derive | v0.8.4 | Unicode-3.0 |
| zerocopy | v0.8.63 | BSD-2-Clause OR Apache-2.0 OR MIT |
| zerofrom | v0.1.8 | Unicode-3.0 |
| zerofrom-derive | v0.1.8 | Unicode-3.0 |
| zeroize | v1.9.1 | Apache-2.0 OR MIT |
| zerotrie | v0.2.5 | Unicode-3.0 |
| zerovec | v0.11.8 | Unicode-3.0 |
| zerovec-derive | v0.11.6 | Unicode-3.0 |
| zmij | v1.0.23 | MIT |
