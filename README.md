package Java;

class Test {

    public static void main(String[] args) {

        Integer i;

        for(i = 0; i <= 100; i++){

            switch(i % 3){

                case 0:
                System.out.println(i + " = Linio");
                break;

            }

            switch(i % 5){

                case 0:
                System.out.println(i + " = IT");
                break;
            }

            if(i % 3 == 0 && i % 5 == 0){
                
                System.out.println(i + " = Linianos");
            }

            System.out.println(" ");
        }

        
    }
}
