//---------------------------------------------------------------------------

#include <vcl.h>
#pragma hdrstop

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;

   //p=pole; liczba=numer pola; default=n; n=nic/puste; moze wypelnic O lub X
   char p1,p2,p3,p4,p5,p6,p7,p8,p9;
   //Kogo tura
   char tura;

   //Sprawdza czy ktos wygral wszystkimi mozliwymi kombinacjami
   void sprawdz()
   {
        if((p1==p2 && p2==p3 && p1!='n') ||
           (p4==p5 && p5==p6 && p4!='n') ||
           (p7==p8 && p8==p9 && p7!='n') ||
           (p1==p4 && p4==p7 && p7!='n') ||
           (p2==p5 && p5==p8 && p2!='n') ||
           (p3==p6 && p6==p9 && p3!='n') ||
           (p1==p5 && p5==p9 && p1!='n') ||
           (p3==p5 && p5==p7 && p3!='n'))
        {
           char * w;
           //Okresla kto wygra³ (na odwrot poniewaz zmienia sie tura po wykonaniu ruchu)
           if(tura=='x')
                w="Wygrywa kó³ko!";
           else
                w="Wygrywa krzy¿yk!";

           Application->MessageBox(w, "Koniec gry", MB_OK);

        }
   }

//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------



void __fastcall TForm1::FormCreate(TObject *Sender)
{
        //Dodawanie grafiki pola gry
        Pole1->Picture->LoadFromFile("img/nic.bmp");
        Pole2->Picture->LoadFromFile("img/nic.bmp");
        Pole3->Picture->LoadFromFile("img/nic.bmp");
        Pole4->Picture->LoadFromFile("img/nic.bmp");
        Pole5->Picture->LoadFromFile("img/nic.bmp");
        Pole6->Picture->LoadFromFile("img/nic.bmp");
        Pole7->Picture->LoadFromFile("img/nic.bmp");
        Pole8->Picture->LoadFromFile("img/nic.bmp");
        Pole9->Picture->LoadFromFile("img/nic.bmp");

        //Przypisanie poczatkowych wartosci
        p1='n'; p2='n'; p3='n';
        p4='n'; p5='n'; p6='n';
        p7='n'; p8='n'; p9='n';
        tura='o';
        gracz->Picture->LoadFromFile("img/osmall.bmp");

        //Zmienia kursor na aktywnym polu
        Pole1->Cursor=crHandPoint;
        Pole2->Cursor=crHandPoint;
        Pole3->Cursor=crHandPoint;
        Pole4->Cursor=crHandPoint;
        Pole5->Cursor=crHandPoint;
        Pole6->Cursor=crHandPoint;
        Pole7->Cursor=crHandPoint;
        Pole8->Cursor=crHandPoint;
        Pole9->Cursor=crHandPoint;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Pole1Click(TObject *Sender)
{

   if(p1=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole1->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p1='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole1->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p1='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole1->Cursor=crDefault;
        sprawdz();
   }

}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole2Click(TObject *Sender)
{
   if(p2=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole2->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p2='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole2->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p2='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole2->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole3Click(TObject *Sender)
{
   if(p3=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole3->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p3='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole3->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p3='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole3->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole4Click(TObject *Sender)
{
   if(p4=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole4->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p4='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole4->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p4='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole4->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole5Click(TObject *Sender)
{
   if(p5=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole5->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p5='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole5->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p5='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole5->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole6Click(TObject *Sender)
{
   if(p6=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole6->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p6='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole6->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p6='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole6->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole7Click(TObject *Sender)
{
   if(p7=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole7->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p7='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole7->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p7='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole7->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole8Click(TObject *Sender)
{
   if(p8=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole8->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p8='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole8->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p8='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole8->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Pole9Click(TObject *Sender)
{
   if(p9=='n')
   {
//Jesli tura gracza O za³aduj obrazek o.bmp na danym polu;
        if(tura=='o')
        {
	        Pole9->Picture->LoadFromFile("img/o.bmp");
                tura='x';
                p9='o';
                gracz->Picture->LoadFromFile("img/xsmall.bmp");
        }
//W przeciwnym wypadku zaladuj x.bmp
        else
        {
	        Pole9->Picture->LoadFromFile("img/x.bmp");
                tura='o';
                p9='x';
                gracz->Picture->LoadFromFile("img/osmall.bmp");
        }
        Pole9->Cursor=crDefault;
        sprawdz();
   }
}
//---------------------------------------------------------------------------


