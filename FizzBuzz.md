public void FizzBuzz(int input)
{
    var answer = ""; 
    if (input % 3 == 0)
    {
        answer = "fizz";  
    }
    if(input % 5 == 0) 
    {
        answer += "buzz"; 
    }
    return answer; 
}