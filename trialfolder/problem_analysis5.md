# file transfer time calculator
    ## problem analysis
        ### inputs:
            1.file size in bytes

        ### output:
            1.time taken to transfer file in days, hours, minutes and seconds.    

       ###  opration:
                1.declare a variable to store file size in bytes, time taken in days, hours, minutes and seconds and intialize the transmission power to 960(rate = 960 bytes/second)
                2.read the inputs
                3.calculate the time taken in seconds as **time taken = file size / rate**
                4.convert the seconds into days, hours and minutes as
                    **days = time taken/86400**
                    **hours = time taken/3600**
                    ** minutes = time taken/ 60**
                5.print the time taken.
                
    ## algorithm design
        ### psedocode
                1.start the program
                2.read file size in bytes 
                3.decalre and initialize the rate (rate = 960)
                4.calculate the time taken in second as **time taken = file size / rate**
                5.convert the time taken in second to days, hours and minutes as
                    **days = time taken/86400**
                    **hours = time taken/3600**
                    ** minutes = time taken/ 60**   
                6.print the time taken in days, hours, minutes and seconds
                7.end the program.    