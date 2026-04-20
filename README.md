# ATM-management-system-C-
minor project in c
//ATM MANAGEMENT SYSTEM
#include <stdio.h>
void main(){
    int amount=50000, pin=2006;
    //card enter
    printf("---ENTER YOUR CARD---\n---अपना कार्ड डालें---\n");
    
    //language 
    int lang;
    printf("---ENTER THE LANGUAGE---\n1.ENGLISH\n2.HINDI\n---भाषा दर्ज करें---\n1.अंग्रेज़ी\n2.हिंदी\n");
    scanf("%d", &lang);
    switch(lang) {
    //ENGLISH
    case 1:
    //CARD TYPE
    int carty;
    printf ("---ENTER YOUR CARD TYPE---\n1.INTERNATIONAL\n2.DOMESTIC\n");
    scanf("%d",&carty);
    switch(carty)
    {
        case 1:
        //INTERNATIONAL
        printf("CONGRATS!!...You have international card\n");
        break;
        
        case 2:
        //DOMESTIC
        //ACCOUNT TYPE
        int accty;
        printf("---ENTER YOUR ACCOUNT TYPE---\n1.SAVINGS\n2.CURRENT\n");
        scanf("%d", &accty);
        switch(accty)
        {
            case 1:
            //SAVINGS
            int amoty;
            printf("---AMOUNT---\n1.DEPOSITE\n2.WITHDRAW\n3.CHECK BALANCE\n");
            switch(amoty)
            {
                case 1:
                //DEPOSITE
                
                
                break;
                 case 2:
                //WITHDRAW
                
                break;
                 case 3:
                //CHECK BALANCE
                
                break;
            }
            break;
            case 2:
            
            break;
        }
        break;
    }
    
    
    
    
    
    
    
    

    
    
    
    
    
    
    
    break;
    
    //HINDI
    case 2:
    
    break;
    }
}
