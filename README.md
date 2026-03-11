 public class Overloading {
    static int sub(int a, int b) {
        return a - b;
    }
    static float sub (float a, float b) {
        return a-b;
    } // different datatype

static int multiply (int a,int b,int c){
        return a*b*c;
}
 static  int multiply (int a,int b){
        return a*b;
    } //different numbers of parameters


    static float divide(int a, float b) {
        return a/b;
    }
   static float divide(float a, int b) {
        return b/a;
    }//different order



    public static void main(String[] args) {


        int SubResult1 = Overloading.sub (9,5);
        System.out.println(SubResult1);
        float SubResult2 = Overloading.sub (9.8f,5.5f);
        System.out.println(SubResult2);

int multiply1 = Overloading.multiply(4,6,3);
        System.out.println(multiply1);
 int multiply2 = Overloading.multiply(4,6);
        System.out.println(multiply2);

      float divide1= Overloading.divide(5,9.5f);
        System.out.println(divide1);
      float divide2= Overloading.divide(5.7f,9);
        System.out.println(divide2);


    }
}
