# Nicholas Benaya

Computer Engineering student at Institut Teknologi Sepuluh Nopember (ITS), Surabaya. Based between Surabaya and Samarinda.

I like understanding how things work underneath: databases that stay consistent under concurrent writes, protocols built directly on sockets, and image algorithms written out from the math instead of called from a library. Most of my work is backend systems, with a side of graphics and networking.

[Email](mailto:nicholasbenaya17@gmail.com) · [Instagram](https://instagram.com/nicholasbenaya_) · [LinkedIn](https://linkedin.com)

---

## What I work with

**Backend:** Node.js, Express, TypeScript, Prisma, MySQL / TiDB, Jest, Supertest, S3-compatible storage

**Systems and graphics:** C, C++, SFML, spatial partitioning (quadtrees, spatial hashing)

**Networking:** Python raw sockets (UDP and TCP), service discovery, multi-VM IPv6 setups, shell and PowerShell scripting

**Vision:** Python, NumPy, OpenCV, Matplotlib

**Client side:** Next.js 14, Tailwind CSS, Flutter and Dart

---

## Projects

### [GameVault API](https://github.com/nicholasbenaya/gamestore-be)
Node.js, Express, Prisma, MySQL/TiDB, Jest, Sharp, S3/MinIO

REST backend for a digital game store with separate user and publisher roles.

- Wallet top-ups and checkout run inside database transactions, so concurrent requests can't corrupt balances. Checkout applies the discount, debits the wallet, adds the game to the buyer's library, and clears it from their wishlist as one atomic step.
- Integration tests with Jest and Supertest run before features are merged.
- Image uploads are processed in memory, converted to lossless WebP with Sharp, then stored in S3-compatible storage.

### [Particle Collision Simulation](https://github.com/nicholasbenaya/collision-simulation)
C++, SFML

Real-time particle collisions where brute-force pair checking (O(N²)) stopped scaling. I replaced it with a spatial hash detector whose cell size scales with particle mass, which keeps the frame rate steady as density goes up. The detector is modular, so it can be benchmarked against the naive approach.

### [UDP Chat with a Custom DNS Service](https://github.com/nicholasbenaya/simple-client-server)
Python, raw sockets

A LAN chat system with no configuration. Rooms register themselves with a local name service over UDP broadcast, and clients discover them the same way. Supports switching rooms while connected, public and private rooms, and clean socket shutdown. No networking frameworks.

### [Computer Vision Labs](https://github.com/nicholasbenaya/PCV_Tugas)
Python, NumPy, Matplotlib

Coursework where I implemented the algorithms myself rather than calling them:

- 2D convolution with zero-padding, plus Gaussian, Laplacian, and Sobel kernels
- Histogram equalization from the CDF
- Point transforms: gamma correction, log scaling, contrast stretching

### [help-umkm](https://github.com/nicholasbenaya/help-umkm)
Next.js 14, React, Tailwind CSS

A monorepo of free websites for small Indonesian businesses. The first one shipped is for Nadia Studio, a florist and makeup artist in Samarinda: a clean minimalist site with built-in analytics and WhatsApp lead tracking, and no database to pay for or maintain.

---

## Currently

Going deeper on backend fundamentals (transactions, testing, storage) and networking below the framework level.
