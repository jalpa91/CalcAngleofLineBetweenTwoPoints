# CalcAngleofLineBetweenTwoPoints
      /**      * Determines the angle of a straight line drawn between point one and two. The number returned, which is a double in degrees, tells us how much we have to rotate a horizontal line clockwise for it to match the line between the two points.     
      * If you prefer to deal with angles using radians instead of degrees, just change the last line to: "return atan2(yDiff, xDiff)"  */  
      
      
      from math import atan2,degrees      
      def GetAngleOfLineBetweenTwoPoints(p1, p2):         
             xDiff = p2.x - p1.x         
             yDiff = p2.y - p1.y         
             return degrees(atan2(yDiff, xDiff))                       
      
      REFERENCE: WikiCode     Available: http://wikicode.wikidot.com/get-angle-of-line-between-two-points     
