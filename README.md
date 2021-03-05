# Deep Learning Basics by J.COp
Disini saya belajar dari materi yang diberikan "JCOp Untuk Indonesia" yang disampaikan langsung oleh mas WiraDKP <br>
Apabila ada yang kurang jelas atau kurang lengkap dari tulisan saya ini bisa langsung mengunjungi github mas WiraDKP sendiri berikut linknya :<br>
https://github.com/WiraDKP

# Starter Guide
Note: sebelum belajar deep learning dari materi "JCOp Untuk Indonesia" sebaiknya ikuti langkah" berikut untuk menginstall miniconda dan menginstall environment dari mas Wira. Untuk materi atau pembelajaran selanjutnya bisa dibuka di repositories saya lainnya seperti (NN with pytorch, CNN with pytorch, RNN with pytorch, Transfer Learning with pytorch, dll.)

## Step 1: Instalasi Miniconda
### **Windows user**
- Download miniconda untuk Python 3.7
    - Klik link ini untuk download: [Miniconda Windows 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe)
    - Note: skip step ini apabila kamu sudah menggunakan Anaconda sebelumnya. Walau demikian, saya akan jelaskan alasan kenapa kamu sebaiknya menggunakan miniconda nanti di course ini.

- Install miniconda
    - Ketika ada pilihan `install for`, pilih `Just Me (recommended)`
    - Untuk `Advanced Options`, silahkan centang `Register Anaconda as my default Python 3.7`
    - Tunggu hingga instalasi selesai

- Jalankan `Anaconda Prompt`

### **Mac user**
- Download miniconda untuk Python 3.7
    - Klik link ini untuk download: [Miniconda Mac OS X 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.pkg)
    - Note: skip step ini apabila kamu sudah menggunakan Anaconda sebelumnya. Walau demikian, saya akan jelaskan alasan kenapa kamu sebaiknya menggunakan miniconda nanti di course ini.

- Install miniconda
    - Install tanpa mengubah opsi apapun
    - Tunggu hingga instalasi selesai

- Jalankan terminal

### **Linux user**
- Download miniconda untuk Python 3.7
    - Klik link ini untuk download: [Miniconda Linux 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)
    - Note: skip step ini apabila kamu sudah menggunakan Anaconda sebelumnya. Walau demikian, saya akan jelaskan alasan kenapa kamu sebaiknya menggunakan miniconda nanti di course ini.
    
- Install miniconda
    - jalankan terminal
    - Install miniconda menggunakan command berikut
        ```
        bash Miniconda3-latest-Linux-x86_64.sh
        ```
    - Ketik `yes` untuk agree dengan license nya, kemudian `yes` lagi untuk `prepend miniconda install location to PATH`
    - Tunggu hingga instalasi selesai
    
- hanya untuk memastikan, tutup dan buka terminal lagi

## Step 2: Instalasi Jupyter 
- Kita akan install 2 hal di base environment
    ```
    conda install --name base jupyter nb_conda_kernels
    ```

## Step 3: Instalasi Environment
- Change directory `cd` ke folder kerja ini
    ```
    cd deep_learning/
    ```
- Jalankan command ini untuk menginstall environment `jcop`
    ```
    conda env create -f env_jcop.yml
    ```

## Step 4: Memastikan environment terinstall dengan baik
- Jalankan command berikut untuk mengecek instalasi dan ikuti instruksi yang dihasilkan
    ```
    python check_installation.py
    ```
- Jika sudah aman, maka akan muncul keterangan berikut, dan kita bisa mulai belajar. Semangat!
    ```
    ✓ jupyter telah terinstall dengan baik
    ✓ nb_conda_kernels telah terinstall dengan baik
    ✓ Environment jcopdl terdeteksi
    ✓ Package telah terinstall dengan baik di dalam environment jcopdl
    ✓ Instalasi berjalan dengan baik. Selamat belajar!
    ```
