<h1 align="center">🎨 Nav Menu Plugin for WordPress</h1>

<p align="center">
  ปลั๊กอิน <b>แถบเมนูนำทางล่างจอสำหรับมือถือ</b> (mobile footer navigation) บน WordPress<br>
  ปุ่ม <b>เข้าสู่ระบบ · สมัคร · เข้าเล่น · โปรโมชั่น · ติดต่อเรา</b> — เลือกได้ <b>14+ ธีมสี</b><br>
  พร้อมปลั๊กอิน <b>Change Link</b> สำหรับปรับลิงก์ปุ่มสมัคร/เข้าสู่ระบบจากหลังบ้านโดยไม่ต้องแก้โค้ด
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WordPress-Plugin-21759B?logo=wordpress&logoColor=white" alt="WordPress">
  <img src="https://img.shields.io/badge/PHP-7.0%2B-777BB4?logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/%E0%B8%98%E0%B8%B5%E0%B8%A1%E0%B8%AA%E0%B8%B5-14%2B-ff69b4" alt="Themes 14+">
  <img src="https://img.shields.io/badge/Mobile--first-%E2%9C%94-2f80ed" alt="Mobile first">
  <img src="https://img.shields.io/badge/Shortcode-%5Bnavstyle%5D-4c1" alt="Shortcode">
</p>

---

## ✨ จุดเด่น

- 📱 **แถบเมนูล่างจอแบบ fixed** แสดงเฉพาะบนมือถือ (`< 768px`) — บนจอ Desktop จะซ่อนอัตโนมัติ ไม่รบกวนหน้าเว็บ
- 🎨 **14+ ธีมสี** ให้เลือกใช้ตามแบรนด์ — Dark Blue, Green, Red, Pink, Gold, Purple, Black และอื่น ๆ
- ⚡ **ใช้งานง่ายด้วย shortcode เดียว** `[navstyle]` วางที่ Footer widget หรือหน้าไหนก็ได้
- 🔗 **ปลั๊กอิน Change Link** ตั้งค่า URL ปุ่ม *สมัคร / เข้าสู่ระบบ* ได้จาก WP Admin แล้ว rewrite ทั้งเว็บให้อัตโนมัติ
- 🧩 **ไม่มี dependency เสริม** — เป็น PHP + CSS ล้วน ติดตั้งแล้วใช้ได้ทันที

---

## 📦 ปลั๊กอินในชุดนี้

### 1) 🧭 Nav Menu Style (แยกตามสี)
เพิ่ม shortcode **`[navstyle]`** ที่เรนเดอร์แถบเมนูล่างจอ พร้อมปุ่ม:

| ปุ่ม | ลิงก์ปลายทาง (ค่าเริ่มต้น) |
|------|-----------------------------|
| เข้าสู่ระบบ | `/signin` |
| สมัคร | `/signup` |
| เข้าเล่น (ตรงกลาง) | `/signup` |
| โปรโมชั่น | `/promotion` |
| ติดต่อเรา | `/line` |

แต่ละธีมจะ `enqueue` ไฟล์ CSS ของสีนั้น ๆ (`assets/<color>-style.css`) — เลือกติดตั้งเพียง **สีเดียว** ต่อเว็บ

### 2) 🔗 Change Link *(change-link.zip)*
ปลั๊กอินหลังบ้านสำหรับ **ตั้งค่า Sign In / Sign Up URL** แล้ว rewrite ลิงก์ `/signin` และ `/signup` ทั่วทั้งเว็บ (ผ่าน output buffering + JS fallback) — เปลี่ยนปลายทางปุ่มได้โดย **ไม่ต้องแก้โค้ดปลั๊กอินเมนู**

> WP Admin → **Change Link** → กรอก *Sign In URL* / *Sign Up URL* → **SAVE**

---

## 🎨 เลือกธีมสี & ดาวน์โหลด

> 📁 = ไฟล์ `.zip` รวมอยู่ในรีโปนี้ด้วย · ที่เหลือดาวน์โหลดผ่านลิงก์

<table>
  <tr>
    <td align="center" width="33%">
      <a href="https://download1591.mediafire.com/efke473gop6gENErO5jODTFcIA3voZBJGqKOrgDm_rW0v2nHWV1-ME4gh3KaA5yX5R3A7yJjBffCYWLweGiF174VEdMIlmO66LDS5Avh5O3VLtktcx_lmyHghsWljUzqBuw-uxf4cgUE4vrgiLjveJGmnrqUbsB7iLVK2_mNs0N2/u7s6ctuznxzcaij/nav-menu-darkblue.zip"><img src="https://i.imgur.com/wy8V36N.png" width="230" alt="Dark Blue"></a><br>
      <sub><b>Dark Blue</b> 📁</sub><br>
      <a href="https://download1591.mediafire.com/efke473gop6gENErO5jODTFcIA3voZBJGqKOrgDm_rW0v2nHWV1-ME4gh3KaA5yX5R3A7yJjBffCYWLweGiF174VEdMIlmO66LDS5Avh5O3VLtktcx_lmyHghsWljUzqBuw-uxf4cgUE4vrgiLjveJGmnrqUbsB7iLVK2_mNs0N2/u7s6ctuznxzcaij/nav-menu-darkblue.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download947.mediafire.com/abqk4bo1wimg5VppWBbMDpzASPIIqiN9fFB5fYXMyxxGORbECay1deAbo4PG4QoeTqDMESgQWT0fZlL1e22YkL7TIHc_PaKQKGHftudvnwaTwltYpoYOPIV79yGf005BfEemzremuqmp3hsQa19BDncIOzcsaywM3A--OtncPlqb/ufsipf9r7e8gl39/nav-menu-green.zip"><img src="https://i.imgur.com/aKwtTiq.png" width="230" alt="Green"></a><br>
      <sub><b>Green</b> 📁</sub><br>
      <a href="https://download947.mediafire.com/abqk4bo1wimg5VppWBbMDpzASPIIqiN9fFB5fYXMyxxGORbECay1deAbo4PG4QoeTqDMESgQWT0fZlL1e22YkL7TIHc_PaKQKGHftudvnwaTwltYpoYOPIV79yGf005BfEemzremuqmp3hsQa19BDncIOzcsaywM3A--OtncPlqb/ufsipf9r7e8gl39/nav-menu-green.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download1325.mediafire.com/wqw5ls0cpx2gESn_dgHAZhqM3jLjMjMY0tREabEP0nzmJ9LVECXi_7Snspq7E9biDm20K20ynky2hRH1PGgreRIXvR3MdMdWlgSHZ_n5mf9iWK_vefUiFKnyrlGVfUA8UHJjxrOExJoFSLnxsVC6Rd6Kf0G7Obmulo5VA5HrVdHw/8r8poq99fh6xtix/nav-menu-greenyellow.zip"><img src="https://i.imgur.com/N4Falna.png" width="230" alt="Green Yellow"></a><br>
      <sub><b>Green Yellow</b> 📁</sub><br>
      <a href="https://download1325.mediafire.com/wqw5ls0cpx2gESn_dgHAZhqM3jLjMjMY0tREabEP0nzmJ9LVECXi_7Snspq7E9biDm20K20ynky2hRH1PGgreRIXvR3MdMdWlgSHZ_n5mf9iWK_vefUiFKnyrlGVfUA8UHJjxrOExJoFSLnxsVC6Rd6Kf0G7Obmulo5VA5HrVdHw/8r8poq99fh6xtix/nav-menu-greenyellow.zip">⬇️ ดาวน์โหลด</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="https://download1503.mediafire.com/pi8oty7w81qgWDRbQwkKz7I8E2poZadIJM8EB5nsvvC2-5ZjYedxYAGtyqGMq71bhYGhPUz1ENE2QBRNyFBP1-wz-lVepD8vRli2nb6dJGPQBDRFzrSf2COJ_HwfcZ5skLzTMMJd3FZGHgmKR4uzDoSGmzrEhueqqe9mJFUsmP0t/tojgeq37jkroyo9/nav-menu-orangered.zip"><img src="https://i.imgur.com/nxRwnGm.png" width="230" alt="Orange Red"></a><br>
      <sub><b>Orange Red</b> 📁</sub><br>
      <a href="https://download1503.mediafire.com/pi8oty7w81qgWDRbQwkKz7I8E2poZadIJM8EB5nsvvC2-5ZjYedxYAGtyqGMq71bhYGhPUz1ENE2QBRNyFBP1-wz-lVepD8vRli2nb6dJGPQBDRFzrSf2COJ_HwfcZ5skLzTMMJd3FZGHgmKR4uzDoSGmzrEhueqqe9mJFUsmP0t/tojgeq37jkroyo9/nav-menu-orangered.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download850.mediafire.com/fly86fft9bggbLZsbfOb67YL-PqywO1g0XqKFaVCycNRPJRpvE8d3N9Kol8B4rm94G-RdOIkPd1nL49L04VPINHaFmQWOkmg7Zk-UZW5pcP_C0JMWV1fb_0f28VWTffsm7LroDIUgyFs8cSE-FMOL6aZ5uNrQ1klABOt48rI46nF/0gjaxoa2hlb7p5h/nav-menu-red.zip"><img src="https://i.imgur.com/GiPfDpq.png" width="230" alt="Red"></a><br>
      <sub><b>Red</b> 📁</sub><br>
      <a href="https://download850.mediafire.com/fly86fft9bggbLZsbfOb67YL-PqywO1g0XqKFaVCycNRPJRpvE8d3N9Kol8B4rm94G-RdOIkPd1nL49L04VPINHaFmQWOkmg7Zk-UZW5pcP_C0JMWV1fb_0f28VWTffsm7LroDIUgyFs8cSE-FMOL6aZ5uNrQ1klABOt48rI46nF/0gjaxoa2hlb7p5h/nav-menu-red.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download1334.mediafire.com/sinuhtwowsqgjXr4yUuACOPL9HtaT48AdM7XMjMzBiIdQA5nSYYJm0OWWK9IqAWRA0Xm7Miui6yfjsOmSpI-ycLekoN7nv2_ZTn1AMvG0rcRfidLTONZOlla9T77jzY4GJgYsbr_Ha3--rwSFN3rbM_Efwpn-NVEekHgNTDydE2D/f3cqphfc8fjhv55/nav-menu-redpink.zip"><img src="https://i.imgur.com/nhkHCCK.png" width="230" alt="Red Pink"></a><br>
      <sub><b>Red Pink</b> 📁</sub><br>
      <a href="https://download1334.mediafire.com/sinuhtwowsqgjXr4yUuACOPL9HtaT48AdM7XMjMzBiIdQA5nSYYJm0OWWK9IqAWRA0Xm7Miui6yfjsOmSpI-ycLekoN7nv2_ZTn1AMvG0rcRfidLTONZOlla9T77jzY4GJgYsbr_Ha3--rwSFN3rbM_Efwpn-NVEekHgNTDydE2D/f3cqphfc8fjhv55/nav-menu-redpink.zip">⬇️ ดาวน์โหลด</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="https://download947.mediafire.com/ahar2vvgfolgWkvuWyfeQ6ahLaq2C1icoQeBhjDoreE7TlHq5pJtW6sCFqcs-w7JR2Qe2OaCQfsl1sI_X2FaX45tTvbMRZQBCM6y-TF7PxO45E35f5l0988GSh7MP8HdVWgwB8KVfGqsJvCpInz0DHWKmFnXxZFsWP_OAf6MmxuP/jbt5oirdswq5d1c/nav-menu-pink.zip"><img src="https://i.imgur.com/ruv5Lwj.png" width="230" alt="Pink"></a><br>
      <sub><b>Pink</b> 📁</sub><br>
      <a href="https://download947.mediafire.com/ahar2vvgfolgWkvuWyfeQ6ahLaq2C1icoQeBhjDoreE7TlHq5pJtW6sCFqcs-w7JR2Qe2OaCQfsl1sI_X2FaX45tTvbMRZQBCM6y-TF7PxO45E35f5l0988GSh7MP8HdVWgwB8KVfGqsJvCpInz0DHWKmFnXxZFsWP_OAf6MmxuP/jbt5oirdswq5d1c/nav-menu-pink.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download1334.mediafire.com/nzft45wxxopgLIfj2TTAUN6Yxg6uolui6P8-MVDjTGMtQs4UIHZ1xAdZGBcasR50geOmt9c2MmdFCeGq6HfSl_Y9XJwa6alLi2q62oG8WClHo03an3hGG837FLHu6xsNsf_tprhWF0aR45KcXBuom5AyGSWx0GYhgpEV8I03LNBcDCY/svjniwwcx8xkvrh/nav-menu-blue.zip"><img src="https://i.ibb.co/R4t9hJsK/blue-softjpg.jpg" width="230" alt="Blue"></a><br>
      <sub><b>Blue</b></sub><br>
      <a href="https://download1334.mediafire.com/nzft45wxxopgLIfj2TTAUN6Yxg6uolui6P8-MVDjTGMtQs4UIHZ1xAdZGBcasR50geOmt9c2MmdFCeGq6HfSl_Y9XJwa6alLi2q62oG8WClHo03an3hGG837FLHu6xsNsf_tprhWF0aR45KcXBuom5AyGSWx0GYhgpEV8I03LNBcDCY/svjniwwcx8xkvrh/nav-menu-blue.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download943.mediafire.com/g09objiiu8tgb2qHHnI6Wpl0lpCSLdi1DYxmV_XxTghO0F3bFEnO6LfxQGIKMhz0ruJTS-B0-QwxnSf9aoZQdWbxDhv4mjITkq_kCPCd9FqY82vmRXZmQdU_hjnIbbSkwohPztTjbE_TgXKjNUjtIBgz2RtPcHu9PlNmKvlyLNcKnf0/vvmkqvxlzws4d2q/nav-menu-gold.zip"><img src="https://i.ibb.co/zhFJfymC/purple.png" width="230" alt="Purple"></a><br>
      <sub><b>Purple</b></sub><br>
      <a href="https://download943.mediafire.com/g09objiiu8tgb2qHHnI6Wpl0lpCSLdi1DYxmV_XxTghO0F3bFEnO6LfxQGIKMhz0ruJTS-B0-QwxnSf9aoZQdWbxDhv4mjITkq_kCPCd9FqY82vmRXZmQdU_hjnIbbSkwohPztTjbE_TgXKjNUjtIBgz2RtPcHu9PlNmKvlyLNcKnf0/vvmkqvxlzws4d2q/nav-menu-gold.zip">⬇️ ดาวน์โหลด</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="https://download1336.mediafire.com/1tyxb5giloagl1NMoWcCHqDls4YiXDKKZdTEB2i-gT2MUXAJlR62n7LsHh4loiRUkgHI0IsMF_okoa-YgNJgWGROH3GPrFwcXkc2s2LExEhWJNco5NX05P8lykLsGSW5uFATBk0rErTsvGQ5FjJdvV1yBqq4wE5iaetfBm2SqEuUWaI/zqql6rteo96919h/nav-menu-gold-yellow.zip"><img src="https://i.ibb.co/4nB29wFG/goldnav.png" width="230" alt="GOLD"></a><br>
      <sub><b>GOLD</b></sub><br>
      <a href="https://download1336.mediafire.com/1tyxb5giloagl1NMoWcCHqDls4YiXDKKZdTEB2i-gT2MUXAJlR62n7LsHh4loiRUkgHI0IsMF_okoa-YgNJgWGROH3GPrFwcXkc2s2LExEhWJNco5NX05P8lykLsGSW5uFATBk0rErTsvGQ5FjJdvV1yBqq4wE5iaetfBm2SqEuUWaI/zqql6rteo96919h/nav-menu-gold-yellow.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download1528.mediafire.com/yswydtzknrlgCMk_ObsuaCmbAWHAveVvNGMnrRQ2BhrN1_sZ3IfmYbHjSgeNiA-JiuRCLAnmBDO8wFtCewyvmgkQDIlGB1G5CPoNKM2R9H1UqOt2aEJPorUX_PguQEyeGQM_p47-e1oMFHSTldIk_n10roH52cMV0NIlRqOuWNtTjAQ/8uvx2lkesnsqt38/nav-menu-softpink.zip"><img src="https://i.ibb.co/C3khYj8S/softpink.png" width="230" alt="SOFT PINK"></a><br>
      <sub><b>SOFT PINK</b></sub><br>
      <a href="https://download1528.mediafire.com/yswydtzknrlgCMk_ObsuaCmbAWHAveVvNGMnrRQ2BhrN1_sZ3IfmYbHjSgeNiA-JiuRCLAnmBDO8wFtCewyvmgkQDIlGB1G5CPoNKM2R9H1UqOt2aEJPorUX_PguQEyeGQM_p47-e1oMFHSTldIk_n10roH52cMV0NIlRqOuWNtTjAQ/8uvx2lkesnsqt38/nav-menu-softpink.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download1322.mediafire.com/ypt5q744wjvgxALoR_Q6EENOMZDkn80Aj6jwsuUpaYEnn1RqFSopHIQJcDz6h55W9VzDeSxOQmQpENfDwkWWFowwOLYsrux18zRwwpwjoVl39CMHx8s0iTTjXLwJHOavAcI-Yq4ue1BCntGzvNADsoKslCxmfn2eCTonusn99wWaDgs/rc482isvf0w43jy/nav-menu-sim-orange.zip"><img src="https://i.ibb.co/9HYvNLQ7/oragesimply.png" width="230" alt="Simple Orange"></a><br>
      <sub><b>Simple Orange</b></sub><br>
      <a href="https://download1322.mediafire.com/ypt5q744wjvgxALoR_Q6EENOMZDkn80Aj6jwsuUpaYEnn1RqFSopHIQJcDz6h55W9VzDeSxOQmQpENfDwkWWFowwOLYsrux18zRwwpwjoVl39CMHx8s0iTTjXLwJHOavAcI-Yq4ue1BCntGzvNADsoKslCxmfn2eCTonusn99wWaDgs/rc482isvf0w43jy/nav-menu-sim-orange.zip">⬇️ ดาวน์โหลด</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="https://download1326.mediafire.com/frhczdk7qsjgRgpEZrP0aIp9QNUnemkBS-T4ltfGfUZkaSL9CaoslkaSiwqsz_dhVnmoilLQrvBuC47NC9-XQ3Ih8OT0t9yyNUVbagmY-VxYDVWBomeuslj85xzyf8W-63VDsOM14pqNxso0jGl9zv2slmsvD0PhcC1e9RBTqRt4NuA/mv19xw03r4khreo/nav-menu-darkpurplr.zip"><img src="https://i.ibb.co/RT6YZ5qk/darkpurplr.png" width="230" alt="Dark Purple"></a><br>
      <sub><b>Dark Purple</b></sub><br>
      <a href="https://download1326.mediafire.com/frhczdk7qsjgRgpEZrP0aIp9QNUnemkBS-T4ltfGfUZkaSL9CaoslkaSiwqsz_dhVnmoilLQrvBuC47NC9-XQ3Ih8OT0t9yyNUVbagmY-VxYDVWBomeuslj85xzyf8W-63VDsOM14pqNxso0jGl9zv2slmsvD0PhcC1e9RBTqRt4NuA/mv19xw03r4khreo/nav-menu-darkpurplr.zip">⬇️ ดาวน์โหลด</a>
    </td>
    <td align="center" width="33%">
      <a href="https://download1530.mediafire.com/yyf154aydapg1MqXZcdL6ccoo_DdcxbLHMj6wP3Yj9qbYVmKEYHA_OtdOGwrxzeYwP06SOqHpqS25clad5lNbbMETEjI7OjG61cfZfDaFhDni1_GiAGDHp0bjLCpu5Zn9_H895VTzeSZFAMY29PRHN62joSp_LgNJDYdDJHPbvLHMQ/4odulkene0x3b70/nav-menu-black.zip"><img src="https://i.ibb.co/chywkXSq/blacknav.jpg" width="230" alt="Black"></a><br>
      <sub><b>Black</b></sub><br>
      <a href="https://download1530.mediafire.com/yyf154aydapg1MqXZcdL6ccoo_DdcxbLHMj6wP3Yj9qbYVmKEYHA_OtdOGwrxzeYwP06SOqHpqS25clad5lNbbMETEjI7OjG61cfZfDaFhDni1_GiAGDHp0bjLCpu5Zn9_H895VTzeSZFAMY29PRHN62joSp_LgNJDYdDJHPbvLHMQ/4odulkene0x3b70/nav-menu-black.zip">⬇️ ดาวน์โหลด</a>
    </td>
  </tr>
</table>

---

## 🚀 วิธีติดตั้ง

1. ดาวน์โหลดไฟล์ `.zip` ของ **ธีมสีที่ต้องการ** (เลือกสีเดียว)
2. เข้า **WP Admin → ปลั๊กอิน → เพิ่มปลั๊กอินใหม่ → อัปโหลดปลั๊กอิน**
3. เลือกไฟล์ `.zip` → **ติดตั้งเดี๋ยวนี้** → **เปิดใช้งาน**
4. (ถ้าต้องปรับลิงก์ปุ่ม) ติดตั้ง **`change-link.zip`** ด้วยวิธีเดียวกัน

---

## 🧩 วิธีใช้งาน

**วางเมนู** — ใส่ shortcode ลงใน Footer widget หรือเนื้อหาเพจ:

```text
[navstyle]
```

**ปรับลิงก์ปุ่ม (ถ้าติดตั้ง Change Link)** — WP Admin → **Change Link** → ตั้ง *Sign In URL* / *Sign Up URL* → **SAVE**
ระบบจะแทนที่ลิงก์ `/signin` และ `/signup` ทั้งเว็บให้อัตโนมัติ

---

## 🗂️ โครงสร้างปลั๊กอิน (แต่ละสี)

```text
nav-menu-styleN/
├─ nav-menu-styleN.php     # ลงทะเบียน shortcode [navstyle] + enqueue CSS
├─ assets/<color>-style.css # สไตล์แถบเมนูของสีนั้น
└─ index.php               # ไฟล์เปล่ากันเข้าถึงโดยตรง (silence is golden)
```

---

## ⚠️ หมายเหตุ

- แถบเมนู **แสดงเฉพาะหน้าจอกว้าง `< 768px`** (มือถือ) โดยตั้งใจ
- ปุ่มค่าเริ่มต้นชี้ไป `/signin` `/signup` `/promotion` `/line` — ปรับ `/signin` `/signup` ได้ผ่าน **Change Link**, ส่วน `/promotion` `/line` ตั้งค่าที่ระบบ redirect ของเว็บ
- ติดตั้งธีมสี **ครั้งละหนึ่งสี** ต่อเว็บ เพื่อไม่ให้ CSS ทับกัน

---

## 👤 เครดิต

- **Nav Menu Style** — Niran.TH
- **Change Link V.2**

<p align="center"><sub>ใช้งานภายในทีม · WordPress footer navigation menu · 14+ color themes</sub></p>
