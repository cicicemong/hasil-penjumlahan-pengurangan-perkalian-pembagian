# hasil-penjumlahan-pengurangan-perkalian-pembagian


    #include<iostream>

    using namespace std;

    int jumlah(){
    int a,b;
    cout<<"Penjumlahan"<<endl;
    cout<<"Masukkan angka 1 : ";
    cin>>a;
    cout<<"Masukkan angka 2 : ";
    cin>>b;
    cout<<"Hasil            : "<<a+b<<endl;
    cout<<endl;
    }
    int kurang(){
    int a,b;
    cout<<"Pengurangan"<<endl;
    cout<<"Masukkan angka 1 : ";
    cin>>a;
    cout<<"Masukkan angka 2 : ";
    cin>>b;
    cout<<"Hasil            : "<<a-b<<endl;
    cout<<endl;
    }
    int kali(){
    int a,b;
    cout<<"Perkalian"<<endl;
    cout<<"Masukkan angka 1 : ";
    cin>>a;
    cout<<"Masukkan angka 2 : ";
    cin>>b;
    cout<<"Hasil            : "<<a*b<<endl;
    cout<<endl;
    }
    int bagi(){
    int a,b;
    cout<<"Pembagian"<<endl;
    cout<<"Masukkan angka 1 : ";
    cin>>a;
    cout<<"Masukkan angka 2 : ";
    cin>>b;
    cout<<"Hasil            : "<<a/b<<endl;
    cout<<endl;
    }
    int main(){
    cout<<endl;
    jumlah();
    kurang();
    kali();
    bagi();
    cout<<endl;

    return 0;
    }
