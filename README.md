#define capacity 3
int Stack[capacity];
int top=-1;
void push(int x){
    if(top<capacity-1){
        top=top+1;
        Stack[top]=x;
        printf("succesfully add item , %d \n" , x);
    }else{
        printf("there is no space \n");
    }
}
int main(){
    printf("implemante my Stack in c . \n");
    push(10);
    push(20);
    push(30);
    push(40);
}
