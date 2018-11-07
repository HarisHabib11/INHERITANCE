using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace empinhar
{
    class emprec
    {
        public int id;
       public string name, desigination, Department, contact, address;

        public void showEmp()
        {

            Console.WriteLine("id : "+ id + "\n Name: "+ name + "\n Desigination: " +desigination+ "\nDepartment:"+Department+"\nAddress:"+address+"\nContact"+ contact );

        }


    }

 class showsalary : emprec
 {

     public string grade;
     public int salary1 = 11000;
     public int salary2 = 20000;
     public int salary3 = 30000;
     public int salary4 = 100000;
     public  void showsalry()
     {
         Console.WriteLine("Grade: "+ grade);
         if(grade == "a" )
         {
             Console.WriteLine("salary: " +salary1);

         }
         else if(grade == "b"){
             Console.WriteLine("salary: "+ salary2 );

         }
         else if (grade == "c")
         {
             Console.WriteLine("Salary : " + salary3);

         }

         else if (grade == "d")
         {

             Console.WriteLine("Salary : " + salary4);
         }

         else
         {
             Console.WriteLine("not include");
         }

     }

 }

    class Program
    {
        static void Main(string[] args)
        {
            showsalary obj = new showsalary();

            obj.id = 101;
            obj.name = "haris";
            obj.contact = "03492077957";
            obj.address = "nk";
            obj.desigination = "manger";
            obj.Department = "it";
            obj.grade = "c";
            obj.showEmp();
            obj.showsalry();
