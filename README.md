
public class About extends Me {

   public static void main(String[] args) {
  
       String reason = "Seek to work in a settings that will dare me extra... 
       and at the same time as allowing me to add to the sustained...
       enlargement and achievment of the organization..";
     
       String[] codes = {"Java", "HTML", "CSS", "Thymleaf", "Javascript", "React"};
       String[] tools = {"Maven", "Hibernate", "Agile", "STS"};
       String[] architecture = {"Microservices","Design System Pattern","Spring MVC","Spring Boot"};
	 Stream.of(architecture)
	          .forEach(System.out::println);    
	 Stream.of(architecture)
              .forEach(name ->System.out.printf("%s ", name));    
	     printAllCodes(codes, reason); 
	     
   }   
	  private static void printAllCodes(String[] codes, String alert) {
		  for(String code : codes) {
		      System.out.println(code);
		      
		  }
		  System.out.println(alert);
		  
	  }
	  
}


