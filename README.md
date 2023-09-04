# Rust Roadmap :crab:
* Bu yol haritasının amacı sizleri Rust'ta başlangıç aşamasından ileri seviyeye taşıyacak şekilde dili kavramak ve günümüzdeki bizim amaçladığımız Smart Contractlar ama bunun haricinde Rust'ın kullanılabildiği diğer sektörlere de zemin hazırlamaktır. [YTU Blockchain](https://linktr.ee/blockchainytu) üyeleri tarafından hazırlanan bu Roadmap Rust'ı yeni öğrenecek adaylara öğretici ve pekiştirici bir zemin sunmayı hedeflemektedir. Ayrıca çeşitli etkinlikler ve iş fırsatlarıyla birlikte Rust geliştiricilerini bir çatı altında topladığımız Discord kanalımıza ve diğer sosyal medya hesaplarımıza [Buradan](https://linktr.ee/blockchainytu) erişebilirsiniz. Şimdilik birçok kaynak İngilizce olarak yol haritasında yer alsa da gelecek dönemlerde ilgili konu başlıkları altında olabildiğince Türkçe kaynağı kendimiz üretmeyi hedefliyoruz.

* Aşağıdaki tablo sırası ile Rust'ta adım adım ilerleyebilmeniz için tasarlanmıştır 👇🏻


## İçerik
| Konu Başlıkları  |
|:------------- |
| [Requirements](#requirements)|
| [How to Learn Better](#how-to-learn-better)|
| [Cargo Package Management](#cargo-package-management)|
| [Common Programming Concepts](#common-programming-concepts)|
| [Ownership](#ownership)|
| [Structs, Enums and Pattern Matching](#structs-enums-and-pattern-matching)|
| [Packages, Crates and Modules](#packages-crates-and-modules)|
| [Common Collections](#common-collections)|
| [Generic Types, Traits and Lifetimes](#generic-types-traits-and-lifetimes)|
| [Writing Automated Tests](#writing-automated-tests)|
| [Iterators and Closures](#iterators-and-closures)|

## Requirement
→ Öncelikle sisteminizde [Rust](https://www.rust-lang.org/tools/install) kurulu olmalı. (Win-Linux-Mac) <br/>
→ Hemen ardından gerekli komutlar ve compiler için [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) kurulu olmalı. (Win-Linux-Mac)<br/>
→ İçerisindeki 94 egzersiz ile birlikte konuları pekiştirmek ve yazma becerisi kazanmak adına [Rustlings](https://github.com/rust-lang/rustlings/) kurmanızı öneriyoruz. (Rustlings, içerisinde konu konu basitten zora olacak şekilde örnekler içeren, sizden bozuk kodu düzeltmenizi isteyen bir uygulama)
→ Rustlings açıklamalı cevap anahtarı için: [Rustlings Solutions](https://github.com/edizzum/rustlings-solutions/tree/rustlings)
## How to Learn Better
→ Yol haritamızdaki ilk adım Rust dilinin genel yazım kurallarına değinmek olacak. Buradaki kaynaklar kavrama güçlüğü çekilebilme ihtimaline karşılık bollandırılmış bir şekilde sunuldu. Kendinize "Ben olmuşum ya!" diyebiliyorsanız gönül rahatlığıyla diğer konuya geçebilirsiniz. Tavsiyemiz [Rustlings](https://github.com/rust-lang/rustlings/) üzerindeki konu sıralamasına göre önce aşağıda vermiş olduğumuz dökümantasyonları iyice kavrayıp örnekleri incelemeniz. Ardından hemen Rustlings'teki örnekleri yapmanız. Bu şekilde öğreniminiz pekişecektir.
## Cargo Package Management
* [Rust Book Hello Cargo](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html)
* [Rust By Example Cargo](https://doc.rust-lang.org/rust-by-example/cargo.html)
* [**(Video)** Using Cargo](https://www.youtube.com/watch?v=_RfxLg6K9oE&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=2)
* [**(Video)** Getting Started with Rust](https://www.youtube.com/watch?v=OX9HJsJUDxA&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=1)
* [Başa dön ⬆](#i̇çerik)
## Common Programming Concepts
* [Rust Book Common Programming Concepts](https://doc.rust-lang.org/book/ch03-00-common-programming-concepts.html)
* [Rust By Example Variables and Mutability](https://doc.rust-lang.org/rust-by-example/variable_bindings.html)
* [Rust By Example Data Types](https://doc.rust-lang.org/rust-by-example/types.html)
* [Rust By Example Functions](https://doc.rust-lang.org/rust-by-example/fn.html)
* [Rust By Example Comments](https://doc.rust-lang.org/book/ch03-04-comments.html)
* [Rust By Example Control Flow](https://doc.rust-lang.org/rust-by-example/flow_control.html)
* [Rust By Example Expressions](https://doc.rust-lang.org/rust-by-example/expression.html)
* [Rust By Example Primitives](https://doc.rust-lang.org/rust-by-example/primitives.html)
* [**(Video)** Common Programming Concepts](https://www.youtube.com/watch?v=2V0JaMVjzws&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=3)
* [**(Video)** Variables, Constants and Shadowing](https://www.youtube.com/watch?v=xYgfW8cIbMA)
* [**(Video)** Data Types](https://www.youtube.com/watch?v=t047Hseyj_k&list=PLzMcBGfZo4-nyLTlSRBvo0zjSnCnqjHYQ&index=4)
* [Başa dön ⬆](#i̇çerik)
## Ownership
* [What is Ownership?](https://medium.com/@AtesBagcabasi/ownershipi-anlamak-b82dd9e27aac)
* [Rust Book Ownership](https://doc.rust-lang.org/book/ch04-00-understanding-ownership.html)
* [Rust By Example Ownership and moves](https://doc.rust-lang.org/rust-by-example/scope/move.html)
* [Rust By Example Borrowing](https://doc.rust-lang.org/rust-by-example/scope/borrow.html)
* [**(Video)** Understanding Ownership in Rust](https://www.youtube.com/watch?v=VFIOSWy93H0&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=4)
* [**(Video)** Memory Management, Heap & Stake](https://www.youtube.com/watch?v=-6cnnNlAvNk&list=PLzMcBGfZo4-nyLTlSRBvo0zjSnCnqjHYQ&index=9)
* [**(Video)** Mülkiyet(Ownership)(Türkçe)](https://www.youtube.com/watch?v=_44mSRHKdqI)
* [Başa dön ⬆](#i̇çerik)
## Structs, Enums and Pattern Matching
* [Rust Book Structs](https://doc.rust-lang.org/book/ch05-00-structs.html)
* [Rust Book Enums and Pattern Matching](https://doc.rust-lang.org/book/ch06-00-enums.html)
* [Rust By Example Structs](https://doc.rust-lang.org/rust-by-example/custom_types/structs.html)
* [Rust By Example Enums](https://doc.rust-lang.org/rust-by-example/custom_types/enum.html)
* [**(Video)** Structs](https://www.youtube.com/watch?v=n3bPhdiJm9I&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=5)
* [**(Video)** Enums and Pattern Matching in Rust](https://www.youtube.com/watch?v=DSZqIJhkNCM&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=6)
* [**(Video)** Option(Enum)(Basic)](https://www.youtube.com/watch?v=JKmkKae-EhM&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=37)
* [Başa dön ⬆](#i̇çerik)
## Packages, Crates and Modules
* [Rust Book Managing Growing Projects with Packages, Crates and Modules](https://doc.rust-lang.org/book/ch07-00-managing-growing-projects-with-packages-crates-and-modules.html)
* [Rust By Example Crates](https://doc.rust-lang.org/rust-by-example/crates.html)
* [Rust By Example Modules](https://doc.rust-lang.org/rust-by-example/mod.html)
* [**(Video)** Modules(Basic)](https://www.youtube.com/watch?v=lx5r7yzl1Ps&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=34)
* [**(Video)** Modules(mod Keyword)(Basic)](https://www.youtube.com/watch?v=KDC8epDY5jw&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=36)
* [**(Video)** Module System Explained!](https://www.youtube.com/watch?v=5RPXgDQrjio&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=7)
* [Başa dön ⬆](#i̇çerik)
## Common Collections
* [Rust Book Vectors](https://doc.rust-lang.org/book/ch08-01-vectors.html)
* [Rust Book Strings](https://doc.rust-lang.org/book/ch08-02-strings.html)
* [Rust Book HashMaps](https://doc.rust-lang.org/book/ch08-03-hash-maps.html)
* [**(Video)** Common Collections](https://www.youtube.com/watch?v=Zs-pS-egQSs&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8&index=8)
* [**(Video)** Vectors(Basic)](https://www.youtube.com/watch?v=GcsAQTMYR1M&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=24)
* [**(Video)** Strings(Basic)](https://www.youtube.com/watch?v=IYYlc26vgyU&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=33)
* [**(Video)** HashMaps(Basic)](https://www.youtube.com/watch?v=sTK8fagTsMk&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=31)
* [Başa dön ⬆](#i̇çerik)
## Generic Types, Traits and Lifetimes
* [Rust Book Generic Types, Traits and Lifetimes](https://doc.rust-lang.org/book/ch10-00-generics.html)
* [Rust By Example Generics](https://doc.rust-lang.org/rust-by-example/generics.html)
* [Rust By Example Traits](https://doc.rust-lang.org/rust-by-example/trait.html)
* [**(Video)** Generic Types](https://www.youtube.com/watch?v=6rcTSxPJ6Bw)
* [**(Video)** Traits](https://www.youtube.com/watch?v=T0Xfltu4h3A)
* [**(Video)** Lifetimes](https://www.youtube.com/watch?v=juIINGuZyBc)
* [Başa dön ⬆](#i̇çerik)
## Writing Automated Tests
* [Rust Book Writing Automated Tests](https://doc.rust-lang.org/book/ch11-00-testing.html)
* [Rust By Example Testing](https://doc.rust-lang.org/rust-by-example/testing.html)
* [**(Video)** Writing and Running Tests(Basic)](https://www.youtube.com/watch?v=3Zg5-evaup0&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL&index=41)
* [**(Video)** Automated Testing](https://www.youtube.com/watch?v=vft2M1aRev4)
* [**(Video)** Testing in Rust(Part 1)](https://www.youtube.com/watch?v=18-7NoNPO30)
* [**(Video)** Testing in Rust(Part 2)](https://www.youtube.com/watch?v=-L4nKAlmH3M)
* [Başa dön ⬆](#i̇çerik)
## Iterators and Closures
* [Rust Book Iterators and Closures](https://doc.rust-lang.org/book/ch13-00-functional-features.html)
* [Rust By Example Closures](https://doc.rust-lang.org/rust-by-example/fn/closures.html)
* [Rust By Example Iterators](https://doc.rust-lang.org/rust-by-example/trait/iter.html)
* [**(Video)** Closures](https://www.youtube.com/watch?v=kZXJvLfjUS4)
* [**(Video)** Iterators](https://www.youtube.com/watch?v=4GcKrj4By8k)
* [Başa dön ⬆](#i̇çerik)
