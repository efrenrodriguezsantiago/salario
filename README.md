#include<iostream>
using namespace std;
int main()
{
	char n_empleado;
	int  p_parcial,p_extras,p_total,n_dia,h_ext,s_diario,p_ex;
	
	cout<<"\nsolicitar nombre del empleado:";cin>>n_empleado;
	cout<<"\nsolicitar sueldo diario:";cin>>s_diario;
	cout<<"\nsolicitar numero de dias trabajadas:";cin>>n_dia;
	
	p_parcial = s_diario * n_dia;  //el programa calcula sueldo diario por numerode horas

	cout<<"sueldo parcial es:"<<p_parcial<<endl;  
	
	cout<<"\nsolicitar numero horas extras trabajadas:";cin>>h_ext;
	
	p_ex = s_diario / 8;
	p_extras = p_ex * h_ext;
	cout<<"la hora extra es:"<<p_extras<<endl;
	
	p_total = p_parcial + p_extras;
	cout<<"el pago total es:"<<p_total<<endl;
	
	
	
	return 0;
}
