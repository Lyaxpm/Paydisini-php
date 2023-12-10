<h1 align="center">Paydisini-php class</h1>

<img src="https://c.tenor.com/aF0ipAtOk9cAAAAC/spy-x-family-anya.gif" alt="Axera" style="width: 50%; height: auto;" >

<p align="center">Axera bio dapat membantu membuat bio anda seperti linktree.</p>

## Installasi

 `$paydisini = new Paydisini('Api_key_kamu');`

## Membuat Transaksi Baru

`$transaction = $paydisini->transaction(
'code_transaction_kamu',
'code_method_pembayaran_paydisini',
'Nominal_transaksi_kamu',
'Catatan_Transaksi_kamu',
'Nomor_telepon');`

<p>Jika fee ingin di tanggung buyer ubah type fee menjadi 1 contohnya <b>'type_fee' => 1</b></p>

## Memeriksa Status Transaksi

`$status = $paydisini->status('code_transaction_kamu');`

## Melihat Payment Channel

`$chanel = $paydisini->chanel();`

## About the Author

Paydisini-php class created by <a href="https://www.freyapp.my.id">Rud Az</a>.

## Donate

Dukung saya di <a href="https://trakteer.id/RudAz" target="_blank">Trakteer</a>
