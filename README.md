<?php
    /* CON INFO */
    $num = "+63 906 062 2253";
    $email = "pagacitacharles6@gmail.com";
    $add = "Sition Malbag Brgy. Sebaste, Sibunag, Guimaras";
    $pos = "GSU Student";
    $fb = "fb@PagacitaCharles"

?>
    <head> 
    <link rel="stylesheet" href="Resume.css">
    </head>
    <main>

        <!--TOP-->
            <section>
                <h1>Charles G. Pagacita</h1>
                    <div>
                        <img src="img/BINI COLET.jpg">
                    </div>

                    <p id="sub1"><?php  echo $pos; ?></p>
                        <hr>
                            <div id="coninfo">
                                <p><?php  echo $num; ?></p>
                                        <p><?php  echo $email; ?></p>
                                            <p><?php  echo $add; ?></p>
                                                <p><?php  echo $fb; ?></p>
                            </div>
                                                    <hr>    

            </section>
             
            <!--ABOUT ME -->
            <section>
                        <h2>About Me</h2>
                            <p><?php  echo "Hi I'm Charles a GSU student that taking a BSIT program. I'm not a consistent honor student but I'm trying  my best to pass all my subject, in that way i can make my parents proud." ?></p>
            </section>

            <!-- EDUCATION -->
            
            <section>
                        <h2>Education</h2>

                            <?php
                                $elem = "Sebaste Fundacion Elem. School, 2016";
                                $sec = "Desiderio C. Gange National High School, 2022";
                                $ter = "Guimaras State University-Mosqueda Campus(3rd Year)";
                            ?>
                                <p class="Ter"><?php echo "Bachelor of Science in Information Technology Major in Web Development"?></p>
                                    <p><?php  echo$ter; ?></p>
                                        <br>
                                            <p class="Sec"><?php echo "Secondary Education"?></p>
                                                <p><?php echo$sec;?></p>
                                                    <br>
                                                        <p class="Pri"><?php echo "Primary Education"?></p>
                                                            <p><?php  echo$elem; ?></p>
            </section>
           
            <section>
                    <h2>Hobbies</h2>
                        <?php
                            $hob1 = "Watching Kdrama & Movie";
                            $hob2 = "Playing Mobile Game";
                            $hob3 = "General cleaning while listening to music";
                            $hob4 = "Playing Guitar";
                            $hob5 = "Practicing on making a website";
                        ?>
                            <li class="hobi1"><?php  echo$hob1; ?></li>
                                <li class="hobi1"><?php  echo$hob2; ?></li>
                                    <li class="hobi1"><?php  echo$hob3; ?></li>
                                        <li class="hobi1"><?php  echo$hob4; ?></li>
                                            <li class="hobi1"><?php  echo$hob5; ?></li>
            </section>

            <!-- CERTIFICATION -->
            <section id="cert">
                    <h2>Certifications</h2>
                        <?php 
                            $police = "Certificate of Attendance ";
                            $tesda = " National Certificate II in Driving";
                        ?>
                            <div class="cert1">
                                <p ><?php  echo "PNP REGIONAL OFFICE<br>6 September 2023 <hr>"; ?></p>
                                    <p id="name"><?php echo$police; ?></p>
                            </div>

                            <div class="cert2">
                                <p><?php  echo "GSAC, October 2023<hr>"; ?></p>
                                    <p id="name2"><?php echo$tesda; ?></p>
                            </div>
            </section>

            <!-- LANGUAGE AND DIALECTS-->
            <section>
                <h2>Languages & Dialect</h2>
                    <?php 
                        $lang1 = "Tagalog";
                        $lang2 = "English";
                        $lang3 = "Hiligaynon";
                        $lang4 = "Bisaya";
                    ?>
                        <p><?php echo$lang1 ?></p>



CSS FILE
*{
    margin: 2%;
}

main{
    border: solid black 1px;
    height: 270%;
    background-color: lightgrey;
}

img{
    width: 140px;
    height: 140px;
    position: absolute;
    right: 9%;
    top: 7%;
    border-radius: 50%;
}

h1{
    margin-top: 5%;
    
    font-size: 40px;
}

#sub1{
    font-size: 30px;
    font-family: Arial, Helvetica, sans-serif;
}

hr{
    border: solid black 1px;
    margin: 0% 2% 0% 2%;
    padding: 0%;

}

#coninfo{
    display: flex;
    justify-content:space-evenly;
    margin: 0%;
    padding: 0%;
}

h2{
    background-color: rgba(146, 143, 143, 0.945);
    padding-left: 5px;
    
}

p {
    font-family: Arial, Helvetica, sans-serif;
    
}



li{
    font-family: Arial, Helvetica, sans-serif;
}

.Ter{
    font-weight: bold;
}

.Sec{
    font-weight: bold;
}

.Pri{
    font-weight: bold;
}
.cert1{
    display: flex;
    
}

#name{
    position: relative;
    right: 30px;
    font-weight: bold;
}

.cert2{
    display: flex;
    
}

.cert2 hr{
    position: relative;
    left: 31px;
}

#name2{
    font-weight: bold;
}
                            <p><?php echo$lang2 ?></p>
                                <p><?php echo$lang3 ?></p>
                                    <p><?php echo$lang4 ?></p>
            </section>

         </main>
