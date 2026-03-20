#include <iostream>
using namespace std;

int main()
{
    string hoten ;
    cout<< "Ho Ten: "<<endl;
    cin>> hoten;
    getline(cin,hoten);

    float diemtoan, diemvan;
    cout<< "Nhap diem toan: "<<endl;
    cin>> diemtoan;

    cout<< "Nhap diem van: "<<endl;
    cin>> diemvan;

    float diemtrungbinh = (diemtoan + diemvan)/2;

    cout << "Diem trung binh la: " << diemtrungbinh << endl;
    return 0;
}
