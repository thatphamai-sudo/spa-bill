# Spa Bill - trang in hoa don 80mm cho Lark Base CRM
Mo: index.html doc du lieu tu URL fragment (#...) do cong thuc LINK HTML trong Base sinh ra.

## Nhat ky
- [2026-08-01][A] Fix bill in ra bi nhat tren may in nhiet: khoi `@media print` ep `color:#000` toan bo (bo mau xam #555/#bbb vi may in 1-bit dither ra luoi cham -> nhin nhat), `-webkit-text-stroke` 0.3px (0.45-0.5px cho tieu de/TONG CONG) de no net chu, tat font-smoothing, tang co chu (nen 12->13px, chu phu 10.5-11->11.5px), doi ke `dashed`/`dotted #bbb` sang net lien den, an emoji khi in, QR them `contrast(3)`. Neu van nhat -> chinh Density/Darkness trong driver may in.
