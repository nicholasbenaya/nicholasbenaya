 <img src="assets/banner.svg" alt="Nicholas Benaya, Computer Engineering student at ITS Surabaya" width="100%">

I'm a Computer Engineering student at ITS Surabaya, based between Surabaya and Samarinda. I like knowing how things work underneath: databases that stay correct under concurrent writes, protocols built straight on sockets, and image algorithms written out from the math instead of imported.

<a href="mailto:nicholasbenaya17@gmail.com"><img src="https://img.shields.io/badge/Email-ee6c4d?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://instagram.com/nicholasbenaya_"><img src="https://img.shields.io/badge/Instagram-7fd1ae?style=for-the-badge&logo=instagram&logoColor=1d2340" alt="Instagram"></a>
<a href="https://www.linkedin.com/in/nicholasbenaya"><img src="https://img.shields.io/badge/LinkedIn-f4d35e?style=for-the-badge&logo=linkedin&logoColor=1d2340" alt="LinkedIn"></a>

## Tools I use

<table>
  <tr>
    <td width="130"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,express,ts,prisma,mysql,jest,aws" alt="Node.js, Express, TypeScript, Prisma, MySQL, Jest, AWS"></td>
  </tr>
  <tr>
    <td><b>Systems and vision</b></td>
    <td><img src="https://skillicons.dev/icons?i=c,cpp,python,opencv" alt="C, C++, Python, OpenCV"></td>
  </tr>
  <tr>
    <td><b>Client side</b></td>
    <td><img src="https://skillicons.dev/icons?i=nextjs,tailwind,flutter,dart" alt="Next.js, Tailwind, Flutter, Dart"></td>
  </tr>
  <tr>
    <td><b>Workflow</b></td>
    <td><img src="https://skillicons.dev/icons?i=git,bash,powershell" alt="Git, Bash, PowerShell"></td>
  </tr>
</table>

## Projects

<table>
  <tr>
    <td width="45%"><img src="assets/p1-transaction.svg" alt="Checkout steps wrapped in one database transaction"></td>
    <td valign="top">
      <h3><a href="https://github.com/nicholasbenaya/gamestore-be">GameVault API</a></h3>
      A REST backend for a digital game store, with separate user and publisher roles. Wallet top-ups and checkout run inside database transactions, so concurrent requests can't corrupt a balance. Uploaded images are converted to lossless WebP with Sharp and stored in S3-compatible storage, and every feature is covered by Jest and Supertest integration tests before merging.<br><br>
      <sub>Node.js, Express, Prisma, MySQL/TiDB, Sharp, S3/MinIO</sub>
    </td>
  </tr>
  <tr>
    <td width="45%"><img src="assets/p2-collision.svg" alt="Particles in a grid, with crowded cells highlighted"></td>
    <td valign="top">
      <h3><a href="https://github.com/nicholasbenaya/collision-simulation">Particle Collision Simulation</a></h3>
      Checking every pair of particles (O(N²)) stops scaling quickly. This engine only compares particles that share a grid cell, and the cell size adapts to particle mass, so frame rates hold up as density grows. The detector is modular, so it can be benchmarked against the brute-force version.<br><br>
      <sub>C++, SFML, spatial hashing</sub>
    </td>
  </tr>
  <tr>
    <td width="45%"><img src="assets/p3-udp.svg" alt="A name service broadcasting to chat rooms"></td>
    <td valign="top">
      <h3><a href="https://github.com/nicholasbenaya/simple-client-server">UDP Chat with a Custom DNS Service</a></h3>
      A LAN chat system that needs no configuration. Rooms register with a local name service over UDP broadcast, and clients find them the same way. It supports switching rooms while connected, public and private rooms, and clean socket shutdown, all without a networking framework.<br><br>
      <sub>Python, raw UDP and TCP sockets</sub>
    </td>
  </tr>
  <tr>
    <td width="45%"><img src="assets/p4-vision.svg" alt="A 3x3 window sliding over image pixels"></td>
    <td valign="top">
      <h3><a href="https://github.com/nicholasbenaya/PCV_Tugas">Computer Vision Labs</a></h3>
      Course exercises where I wrote the algorithms myself: 2D convolution with Gaussian, Laplacian and Sobel kernels, histogram equalization from the CDF, and point transforms like gamma correction, log scaling and contrast stretching.<br><br>
      <sub>Python, NumPy, Matplotlib</sub>
    </td>
  </tr>
  <tr>
    <td width="45%"><img src="assets/p5-site.svg" alt="A small business website with a WhatsApp button"></td>
    <td valign="top">
      <h3><a href="https://github.com/nicholasbenaya/help-umkm">help-umkm</a></h3>
      Free websites for small Indonesian businesses. The first one is for Nadia Studio, a florist and makeup artist in Samarinda: a minimalist site with built-in analytics and WhatsApp lead tracking, and no database to pay for or maintain.<br><br>
      <sub>Next.js 14, React, Tailwind CSS</sub>
    </td>
  </tr>
</table>
