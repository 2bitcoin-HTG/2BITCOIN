# 2Bitcoin (2BTC)

**2Bitcoin (2BTC)** là một blockchain phi tập trung được phát triển dựa trên Bitcoin với tổng cung lớn hơn và khả năng ứng dụng cao hơn.

## **Tính năng chính**
1. **Tổng cung**: 39 triệu 2BTC.
2. **Thời gian tạo khối**: 10 phút.
3. **Thuật toán đồng thuận**: Proof-of-Work (SHA-256).

## **Hướng dẫn cài đặt**
1. Clone mã nguồn:
   ```bash
   git clone https://github.com/2bitcoin-HTG/2bitcoin.git
   cd 2bitcoin
   ```

2. Cài đặt các thư viện cần thiết:
   ```bash
   sudo apt-get install build-essential libtool autotools-dev automake pkg-config bsdmainutils python3
   sudo apt-get install libevent-dev libboost-dev libboost-system-dev libboost-filesystem-dev
   ```

3. Biên dịch blockchain:
   ```bash
   ./autogen.sh
   ./configure
   make -j4
   ```

4. Khởi chạy blockchain:
   ```bash
   src/bitcoind -daemon
   ```

5. Tạo ví và bắt đầu khai thác:
   ```bash
   src/bitcoin-cli getnewaddress
   src/bitcoin-cli generatetoaddress 1 <your_address>
   ```

## **Liên hệ**
- **Website**: [2Bitcoin.org](https://2bitcoin.org)
- **Email**: support@2bitcoin.org
- **Giấy phép**: MIT License
