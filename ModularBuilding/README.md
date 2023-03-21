# ModularBuilding

## Principle

Set of .dxf files to be used for laser cutting / CNC.
The idea is to have has few pieces as possible to spam production and make modular buildings (stackable, juxtaposable blocks).

For an unitary block you need 4 walls and 2 floors (top and bottom). See this lovely diagram:

                                                                                                                
                                                                                                                
                                                                      @           @@@                           
                                                                      @@         @@@@@@                         
                                  @@@             @                   @@@@      @@    @@@                       
                                 @@ @@           @@                   @  @@@   @@      @@@@                     
                               @@@   @@        @@@@                   @    @@@@          @@@                    
                             @@@      @@     @@@  @                   @      @             @@@                  
                           @@@         @    @@    @                   @@                     @@@                
                          @@@          @@ @@@     @                   @@                       @@@              
                        @@@             @@@       @                   @@                         @@@            
                      @@@                         @                   @@                          @@@@          
                     @@                           @                   @@            @               @@@         
                   @@@                            @                   @@            @@@              @@         
                   @@                             @@                  @@            @@@@@             @         
                   @             @                @@                  @@            @@  @@@@          @@        
                  @@           @@@                @@                  @@            @@    @@@@        @@        
                  @@         @@@ @@               @@                  @@            @@@@    @@         @        
                  @@        @@   @@               @@                  @@              @@@@   @         @@@      
                  @       @@@  @@@                @@                  @@                @@@@@@           @@     
                 @@      @@   @@                  @@         @@@@     @@                   @@@            @@@   
                 @@      @  @@@                   @@        @@  @@    @@                     @              @@  
                 @@      @@@@                     @@      @@@    @@@                                         @@ 
               @@@       @@                       @      @@        @@                                         @ 
              @@@        @                             @@@          @@                                        @ 
            @@@                                      @@@             @@@    @@@                               @ 
          @@@                               @@      @@                 @@  @@@@@                              @ 
         @@                                @@@@   @@@                   @@@@   @@                             @ 
        @@                               @@@  @@ @@                             @@@                           @ 
        @@                              @@     @@@                                @@                          @ 
        @@                            @@@                                         @@                          @ 
        @@                           @@@                                         @@                           @ 
        @@                            @@                                         @@                           @ 
        @@                             @@                                         @@@                         @ 
        @@                            @@@                                           @@                        @ 
        @@                           @@                                              @@@                      @ 
        @@                         @@@                                                 @@                     @ 
        @@                        @@                                                    @@                    @ 
        @@                      @@@                                                      @@@                  @ 
        @@                     @@                                                          @@                 @ 
        @@              @@   @@@      @@                                                  @@@@@      @@@      @ 
        @@              @@@@@@       @@@@                                                @@@  @@    @@@@      @ 
        @@              @@@@@      @@@  @@@                                            @@@ @@  @@@ @@ @@      @ 
        @@              @@  @@   @@@      @@                                          @@    @@   @@@  @@      @ 
         @              @@   @@@@@         @@@                                      @@@      @@  @@   @@      @ 
         @              @@     @             @@                                    @@         @@@@    @@      @ 
         @           @@ @@                    @@@                                 @@           @      @@      @ 
         @         @@@  @@                      @@                              @@                    @@      @ 
         @        @@    @@                       @@                            @@                     @@      @ 
         @        @     @@                        @@@                        @@@                      @@      @ 
         @        @     @@                          @@                      @@                        @@      @ 
         @       @@     @@                           @@@                    @                         @@      @ 
         @       @@     @@                             @                   @@                         @@      @ 
         @       @@     @@                             @@                  @@                         @@      @ 
         @       @@     @@             @               @@                  @                          @@@@    @ 
         @@      @@     @@            @@@@              @                  @                          @@ @@@  @ 
         @@    @@@      @@            @@@@@             @                 @@                          @@   @@@@ 
         @@   @@        @@            @@  @@@@          @@                @@                          @@    @@@ 
         @@ @@@         @@            @@    @@@@        @@                @@         @@@              @@      @ 
         @@@@           @@            @@      @@         @               @@         @@@@              @@        
         @@@            @@             @@@@   @@         @@             @@        @@@ @@              @@        
                         @               @@@@@@@          @@@         @@@       @@@   @@              @@        
                         @                  @@@@            @@       @@        @@    @@@              @@        
                         @                     @             @@@   @@@         @@   @@                 @        
                         @                                     @@@@@            @@@@@                  @        
                         @                                      @@              @@@                    @        
                         @                                       @              @                      @        
                         @                                       @                                     @        
                         @                                       @                                     @        
                         @                                       @                                     @        
                         @                                       @                                     @        
                         @                                       @                                     @        
                         @                                       @                                     @        
                         @                                       @                                     @        
                         @                                       @                                     @        
                         @@                                      @                                     @        
                         @@                                      @                                     @        
                         @@             @                        @                                     @        
                         @@             @@@                      @                                     @@       
                         @@      @@@    @@@@@                    @                                     @@       
                         @@     @@ @@@ @@  @@@@                  @                                     @@       
                         @@    @@    @@@@    @@@                 @                                     @@       
                          @@@ @@       @@      @                 @                                     @@       
                            @@@                @@                @                                     @@       
                                               @@                @                                     @@       
                                               @@@@              @                                     @@       
                                                 @@@@            @                    @@@    @@       @@        
                                                    @@@@         @                   @@@@  @@@@@     @@         
                                                      @@@        @                 @@@ @@@@@    @@  @@          
                                                        @        @                 @    @@       @@@@           
                                                        @        @                 @@   @         @@            
                                                        @@       @                 @@                           
                                                        @@       @               @@@                            
                                                        @@       @              @@                              
                                                         @       @            @@@                               
                                                         @       @           @@                                 
                                                         @@      @           @@                                 
                                                         @@      @           @@                                 
                                                          @@@    @@          @@                                 
                                     `                     @@@@  @@          @                                  
                                                             @@@@@@       @@@@                                  
                                                               @@@@     @@@@                                    
                                                                 @   @@@@                                       
                                                                  @@@@@                                         
                                                                  @@                                            



## Details
Today there is only plans for 3mm thick material (MDF, cardboard or whatever you want).
It is still a work in progress, but the idea is to be able to build modular buildings with bridges, ladders etc... It would probably best used in futuristic games (Infinity was the targeted game at first), but it must match anything you can decorate those blocks with.


## Versions
v1: A full feature of blocks + ladders + bridges + some special walls. Beware that those are not optimized (and will never be) - you might have redundant cutting lines and some minor issues. There won't be any work on this version and it might be deleted as soon as v2 is done.

v2: A new, optimized version. No redundant lines, no issues so far. Only walls and floors for now but this new design is in progress. Includes some 3mm holes to insert 3mm round magnets, easing horizontal assembly and addition of futures add-ons.
