//---------------------------------------------------------------------------

#include <vcl.h>
#pragma hdrstop

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;
int i=0;
int x=0;
//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
Edit1->Text=x;
Image3->Hide();
Image4->Hide();
Image5->Hide();
Image6->Hide();
Image7->Hide();
Image8->Hide();
Image9->Hide();
Image10->Hide();
Image11->Hide();

}
//---------------------------------------------------------------------------



void __fastcall TForm1::Button1Click(TObject *Sender)
{
i=1;
Image1->Canvas->Pen->Color=clMaroon;
Image1->Canvas->Brush->Color=clMoneyGreen;
Image1->Canvas->Rectangle(10,360,60,390);
Image1->Canvas->Rectangle(10,350,20,360);
Image1->Canvas->Rectangle(30,350,40,360);
Image1->Canvas->Rectangle(50,350,60,360);
Image1->Canvas->Rectangle(60,270,130,390);
Image1->Canvas->Rectangle(130,320,180,390);
Image1->Canvas->Rectangle(180,290,230,390);
Image1->Canvas->Brush->Color=clMedGray;
TPoint a[4]={Point(50,270), Point(140,270), Point(95,200), Point(50,270)};
Image1->Canvas->Polygon(a, 3);
TPoint b[5]={Point(180,290), Point(170,270), Point(240,270), Point(230,290), Point(180,290)};
Image1->Canvas->Polygon(b, 4);
Image1->Canvas->Rectangle(170,270,240,240);
Image1->Canvas->Rectangle(170,240,180,230);
Image1->Canvas->Rectangle(190,240,200,230);
Image1->Canvas->Rectangle(210,240,220,230);
Image1->Canvas->Rectangle(230,240,240,230);
TPoint c[7]={Point(80,390), Point(80,360), Point(90,350), Point(100,350), Point(110,360), Point(110,390), Point(80,390)};
Image1->Canvas->Polygon(c, 6);
TPoint d[6]={Point(70,340), Point(70,310), Point(80,300), Point(90,310), Point(90,340), Point(70,340)};
Image1->Canvas->Polygon(d, 5);
TPoint e[6]={Point(100,340), Point(100,310), Point(110,300), Point(120,310), Point(120,340), Point(100,340)};
Image1->Canvas->Polygon(e, 5);
        Image1->Canvas->MoveTo(80,300);
        Image1->Canvas->LineTo(80,340);
        Image1->Canvas->MoveTo(70,320);
        Image1->Canvas->LineTo(90,320);
        Image1->Canvas->MoveTo(70,330);
        Image1->Canvas->LineTo(90,330);
        Image1->Canvas->MoveTo(110,300);
        Image1->Canvas->LineTo(110,340);
        Image1->Canvas->MoveTo(100,320);
        Image1->Canvas->LineTo(120,320);
        Image1->Canvas->MoveTo(100,330);
        Image1->Canvas->LineTo(120,330);
Image1->Canvas->Rectangle(70,280,80,270);
Image1->Canvas->Rectangle(90,280,100,270);
Image1->Canvas->Rectangle(110,280,120,270);
Image1->Canvas->Rectangle(30,380,40,370);
Image1->Canvas->Rectangle(130,320,140,310);
Image1->Canvas->Rectangle(150,320,160,310);
Image1->Canvas->Rectangle(170,320,180,310);
Image1->Canvas->Rectangle(140,360,150,330);
Image1->Canvas->Rectangle(160,360,170,330);
        Image1->Canvas->MoveTo(140,350);
        Image1->Canvas->LineTo(150,350);
        Image1->Canvas->MoveTo(140,340);
        Image1->Canvas->LineTo(150,340);
        Image1->Canvas->MoveTo(160,350);
        Image1->Canvas->LineTo(170,350);
        Image1->Canvas->MoveTo(160,340);
        Image1->Canvas->LineTo(170,340);
Image1->Canvas->Rectangle(190,330,200,310);
Image1->Canvas->Rectangle(210,330,220,310);
        Image1->Canvas->MoveTo(190,320);
        Image1->Canvas->LineTo(200,320);
        Image1->Canvas->MoveTo(210,320);
        Image1->Canvas->LineTo(220,320);
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button2Click(TObject *Sender)
{
if (!Timer1->Enabled)
        Timer1->Enabled=true;
else
        Timer1->Enabled=false;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Timer1Timer(TObject *Sender)
{
Form1->DoubleBuffered=true;
        Image2->Hide();
        Image3->Show();
        Repaint();
        Sleep(200);
        Image3->Hide();
        Image4->Show();
        Repaint();
        Sleep(200);
        Image4->Hide();
        Image5->Show();
        Repaint();
        Sleep(200);
        Image5->Hide();
        Image6->Show();
        Repaint();
        Sleep(200);
        Image6->Hide();
        Image7->Show();
        Repaint();
        Sleep(200);
        Image7->Hide();
        Image8->Show();
        Repaint();
        Sleep(200);
        Image8->Hide();
        Image9->Show();
        Repaint();
        Sleep(200);
        Image9->Hide();
        Image2->Show();

}
//---------------------------------------------------------------------------


void __fastcall TForm1::Button3Click(TObject *Sender)
{
Form1->DoubleBuffered=true;
Image10->Left=376;
Image10->Top=72;
        Timer1->Enabled=false;
        Image2->Hide();
        Image3->Show();
        Repaint();
        Sleep(200);
        Image3->Hide();
        Image4->Show();
        Repaint();
        Sleep(200);
        Image4->Hide();
        Image5->Show();
        Repaint();
        Sleep(200);
        Image5->Hide();
        Image6->Show();
        Repaint();
        Sleep(200);
        Image6->Hide();
        Image7->Show();
        Repaint();
        Sleep(200);
        Image7->Hide();
        Image8->Show();
        Repaint();
        Sleep(200);
        Image8->Hide();
        Image9->Show();
        Repaint();
        Sleep(200);
        Image9->Hide();
        Image2->Show();

for (; Image10->Left>150 ;){
Image10->Show();
Image10->Left-=10;
Image10->Top+=10;
Repaint();
Sleep(50);
}
Image10->Hide();
if (i==1){
i=0;
x=x++;
Edit1->Text=x;
Image11->Show();
MediaPlayer2->Play();
Timer2->Enabled=true;
}
}
//---------------------------------------------------------------------------



void __fastcall TForm1::Timer2Timer(TObject *Sender)
{
  if (Image11->Height>300){
  Sleep(300);
  Image1->Picture->Bitmap=NULL;
  Image1->Picture->LoadFromFile("fire.bmp");
  Image11->Hide();
  Image11->Height=129;
  Image11->Top=224;
  Image11->Width=177;
  Image11->Left=72;
  Timer2->Enabled=false;
  Timer1->Enabled=true;
  }
  Image11->Height+=6;
  Image11->Top-=3;
  Image11->Width+=6;
  Image11->Left-=3;

}
//---------------------------------------------------------------------------



void __fastcall TForm1::Button4Click(TObject *Sender)
{
x=0;
Edit1->Text=x;
}
//---------------------------------------------------------------------------


