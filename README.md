# HALF_ADDER
## AIM
#### To Simulate the Half Adder using Vivado software
## APPARATUS REQUIRED
#### Vivado 2023.2 Software
## PROCEDURE
    *
    *
    *
    *
    *
    *
    *
## PROGRAM  
     module HA(a,b,sum,carry);
     input a,b;
     output sum,carry;
     xor g1(sum,a,b);
     and g2(carry,a,b);
     endmodule
## Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
## Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
## OUTPUT
![half adder output](https://github.com/NitheshKumar-B/EXP-1/assets/161724980/34bf5e77-672b-4131-a606-e91460b8e10e)
## RESULT
#### Thus the halfadder program is studied and simulated using the software successfully

# FULL ADDER
## AIM
#### To Simulate the Half Adder using Vivado software
## APPARATUS REQUIRED
#### Vivado 2023.2 Software
## PROCEDURE
    *
    *
    *
    *
    *
    *
    *
 ## PROGRAM
    module FA(a,b,c,sum,carry);
    input a,b,c;
    output sum,carry;
    assign sum=a^b^c;
    assign carry=(a&b)|(b&c)|(c&a);
    endmodule 

# Truth Table
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/02ead8f5-d958-4c89-ac51-368ca086cf41)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e427a3bbc)
## OUTPUT
![full adder output](https://github.com/NitheshKumar-B/EXP-1/assets/161724980/9a325104-e7cd-4134-ac5a-1ea6840968ef)
## RESULT
#### Thus the fulladder  program is studied and simulated using the software successfully

# HALF SUBTRACTOR
## AIM
#### To Simulate the Half Adder using Vivado software
## APPARATUS REQUIRED
#### Vivado 2023.2 Software
## PROCEDURE
    *
    *
    *
    *
    *
    *
    *
# Truth Table
![image](https://github.com/NitheshKumar-B/EXP-1/assets/161724980/e2723d53-637c-4a27-bc05-8dc4abf65d61)
# Circuit Diagram


    
