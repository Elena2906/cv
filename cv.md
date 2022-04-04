# ***Elena Kaporikova***
## :woman_office_worker: *future manager-economist of information systems*
**Contact information:**

:telephone_receiver:Phone: +375(29)697-30-89

:e-mail:E-mail: elenakaporikova29@gmail.com

:paintbrush:Telegram: [Alena_say29](https://web.telegram.org/z/)

:pen:Vkontakte: [Elena Kaporikova](https://vk.com/id285859304)
## 	:airplane:*The beginning of a long journey:*

*At the end of the school, there was an interest in the subject of computer science, on which they gave a knowledge base that allowed them to start a more in-depth study of the field of information technology.*

*Soon after studying different areas of the subject and participating in competitions, I began to look for a profession that would be related to what I like. After entering VSU named after P. M. Masherov, I started studying programming languages, economic disciplines, computer graphics and animation, English, and so on.*

*At the moment, I continue to study those areas that are related to my future field of activity, specifically, information technology.*

*I believe that we need to build and walk our path to success on our own, because the more mistakes we make, the more we appreciate what we have.*
## :memo:*Skills and proficiency:*
* **HTML5**
* **Git, GitHub**
* **VS Code, C++, Pascal, Assembler**
* **Adobe Photoshop, Adobe Dreamweaver**
* **Inkscape, Blender**
* **Cmd Windows, cmd Linux**
## 	:computer:*Code example:*
*Purpose of the task: to show the work of one of the principles of object-oriented programming, which is known as inheritance, in a problem involving finding the volume of a sphere and a cylinder.*
```
#include<iostream>
#include <cmath> 
#include <string>
using namespace std;
class Sphere {
protected:
	double r;
public:
	Sphere(double r) {
		this->r = r;
	}
	double get_r()
	{
		return r;
	}
	double  VolumeS(double r) {
		return (r * r * r * 3.14 * 1.3);
	}
};
class Cylinder : public Sphere {
	double h;
public:
	Cylinder(double h, double r) : Sphere(r)
	{
		this->h = h;
	}
	double VoiumeC(double r, double h) {
		return  3.14 * r * h * r;
	}
};
int main()
{
	setlocale(LC_ALL, "ru");
	double x, y;
	cout << "Введите радиус и высоту: ";
	cin >> x>>y;
	if (x < 0 || y < 0) {
	cout<< "error";
}
else{
		Cylinder c(x, y);
		cout << c.VoiumeC(x, y) << endl;
		Sphere sh(x);
		cout << sh.VolumeS(x) << endl;
		Cylinder c(x, y);
		cout << c.VoiumeC(x, y) << endl;
	}
	system("pause");
	return 0;
}
```
## :mortar_board:*Courses:*
* **Self-study HTML**([Work](https://github.com/Elena2906/HTML/blob/main/HTML))
# <img src="https://user-images.githubusercontent.com/102890678/161447810-cfee08c3-fa6a-4482-95e6-e894124e5d78.png" width="340" height="140" />
* **Self-study Blender**
# <img src="https://user-images.githubusercontent.com/102890678/161447989-1d161247-1cf4-49e9-89c4-cac137c2efe1.png" width="340" height="140" />
* **Self-study Adobe Photoshop**
# <img src="https://user-images.githubusercontent.com/102890678/161448392-ad1197f7-12ff-4f17-ae31-2bcc77ff0fde.png" width="340" height="140" />
## :england:*Languages:*
* **English- Intermediate/Upper-intermediate**
# <img src="https://user-images.githubusercontent.com/102890678/161447216-29a8e5c2-551e-4f15-b085-fbe6800f9414.png" width="340" height="140" />


