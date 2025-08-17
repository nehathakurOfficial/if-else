
    class Solution {
    public:


    void studentGrade(int marks) {
    int marks = 95;
    if( marks >= 90){
        cout<<"Grade  A "<<endl;
    }
    else if(marks >= 70){
        cout<<" Grade B"<<endl;
    }
    else if(marks >= 50){
        cout<<" Grade C"<<endl;

    }
    else if( marks >= 35){
        cout<<"Grade D"<<endl;
    }
    else{
        cout<<" fail";
    }
    }
    };

    int main(){
    solution s;
    s.studentGrade(95);
    }
