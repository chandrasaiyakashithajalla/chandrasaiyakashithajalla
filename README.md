public class VerifyDate{
//method to handle potential checks against two dates
public Static Date CheckDate(Date date1,Date date2){
//if date2 is within the next 30 days of date1,use date2, Otherwise use the end of the month{
  if(Date)With30Days(date1,date2)){
   return date2;
  }else{
   return SetEndOfMonthDate(date1);
  }
}
//method to check if date2 is within the next 30 days of date1
 private static Boolean DateWithin30Days(Date date1, Date date2){
  //check for date2 being in the past
     if( date2 < date1) { return false; }
 }
       //check that date2 is within(>=) 30 days of date1
       Date date30Days = date1.addDays(30);//Date date 30days away from date1
       if( date2 >= date30Days ) { return false; }
       }
       //method to return the end of the month of a given date
       private static Date SetEndOfMonthDate(Date date1)
       {
         integer totalDays = Date.daysinMonth(date1.year(),date1.month(), totalDays);
         return lastDay;
       }
      }
        
        
