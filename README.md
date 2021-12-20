# Lecture-15-pt.2

Good morning and bye

    #include <iostream>  
    using namespace std;

    string greetings(int time) {
      if (time < 12) {
        return "Good Morning";
      }
      else if(time >=12 && time <=17)  {
        return "Good Afternoon";
      }
      else if (time >= 18 && time <= 21) {
        return "Good Evening";

      }
      else if (time >= 22 && time <= 24) {
        return "Good Night";
      }

    }
    int main() {
      cout << "What time is it? Enter the time in 24 format" << endl; 
      int userInput; 
      cin >> userInput; 
      cout << greetings(userInput) << endl;
      return 0;
    }
