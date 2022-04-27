# Multidimensional-array-in-PHP
Multidimensional array in PHP
<html>
   <body>
      
      <?php
         $diemThi = array(
            "wild" => array
            (
               "monVatLy" => 7,
               "monToan" => 8,
               "monHoa" => 9
            ),
            
            "manh" => array
            (
               "monVatLy" => 7,
               "monToan" => 9,
               "monHoa" => 6
            ),
            
            "huong" => array
            (
               "monVatLy" => 8,
               "monToan" => 8,
               "monHoa" => 9
            )
         );
         
         /* access multidimensional array values ​​*/
         echo "Hoang's Physics test score is: " ;
         echo $diemThi['wild']['monVatLy'] . "<br />";
         
         echo "Manh's Math test score is: ";
         echo $diemThi['manh']['monToan'] . "<br />";
         
         echo "Huong's chemistry test score is: " ;
         echo $diemThi['huong']['monHoa'] . "<br />";
      ?>
   
   </body>
</html>
