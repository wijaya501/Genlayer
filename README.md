# GenLayer Voting Project

Project Intelligent Contract sederhana di GenLayer Testnet.

## Deskripsi
Contract `Voting.gen` ini adalah sistem voting on-chain dengan AI verification.
AI akan mengecek setiap alasan vote agar tidak spam/tidak relevan.

## Fitur
- ✅ Buat voting baru
- ✅ Voting dengan alasan wajib
- ✅ AI check: alasan harus relevan dengan topik
- ✅ Lihat hasil voting real-time

## Cara Pakai
1. Deploy `Voting.gen` di GenLayer Testnet
2. Panggil fungsi `createVote("Topik Voting")`
3. Panggil fungsi `vote(voteId, true, "Alasan kamu")`
4. Lihat hasil dengan `getResults(voteId)`

## Teknologi
- Bahasa: GenLayer `.gen`
- Network: GenLayer Testnet

Dibuat untuk GenLayer Builder Program
