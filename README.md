# hemi-node
https://cryptorank.io/drophunting/hemi-network-activity420
Hướng dẫn chạy Node Hemi network

Chạy node trên Web và trên Windows

🎥 Video hướng dẫn : https://youtu.be/8z1xWmpYdUI

1️⃣Chạy node trên Web
🔹 Truy cập: https://pop-miner.hemi.xyz/
🔹Chọn "Open web PoP Miner"
🔹 Tạo ví mới và lưu trữ private key thật kỹ.
🔹 Dự án sẽ cung cấp cho bạn một địa chỉ tBTC để faucet.

🚰 Faucet tBTC bằng cách:

🔹 Truy cập Discord: https://discord.gg/invite/hemixyz
👉🏻https://discord.com/channels/1202677849887080508/1230886659222929418
🔹 Vào kênh faucet và xài lệnh /tbtc-faucet địa chỉ ví
🔹Dán địa chỉ ví vào và đợi con bot gửi token.
🔹 Qua lại trang chạy node đợi nó xác nhận mất vài phút rồi tiếp tục là được.

❗️Vì hiện tại bước này đang lỗi trên Web Dev đang khắc phục, nên ta làm thêm bước sau " Chạy CLI trên máy tính bằng cmd"

2️⃣ Chay node CLI trên máy tính bằng cmd

👉🏻Bài hướng dẫn: https://x.com/MintyKoki/status/1838111900984611261
1. Tải flie
2. Mở cmd
Win + R
Gõ : cmd ấn enter
3. gõ
cd "đường dẫn file"
dir ấn enter 
4.popmd.exe --help
5. I Import pravite key vào node
set POPM_BTC_PRIVKEY=<private_key>
set POPM_STATIC_FEE=<fee_per_vB_integer>
set POPM_BFG_URL=wss://testnet.rpc.hemi.network/v1/ws/public 
6. Chay node
popmd.exe -> enter

🔹Check trạng thái Node:
Dán địa chỉ ví hoặc public key vào và check
-https://testnet.popstats.hemi.network/
-https://mempool.space/testnet

3️⃣Hướng dẫn cách add ví chạy Node vào Hemi

1 : Sử dụng Privatekey sau đó Import vào ví Metamask của mình (ai mất key thì tạo luôn Node mới rồi làm lại từ đầu).

2: Truy cập connections
: https://points.absinthe.network/hemi/d/connections

3 :Kéo xuống dưới chọn vào "Add Wallet" rồi kết nối ví chạy Node vào là xong.

Nguồn : Gem Research & một số bên khác
