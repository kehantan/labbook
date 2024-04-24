Count plaques with ImageJ
=========================

#. Take photo of each well. 

    * Take photo against transilluminator in white light mode for better contrast. 

#. Import photo to laptop. 
#. Open the image of the well with ImageJ. 

    * For easier manipulation, can crop the surrounding of the wells with any software before open with ImageJ. 

#. Image > Type > 8-bit
#. Image > Adjust > Brightness/contrast

    * Reduce the backgroud noise as much as possible by adjusting the brightness and contrast. This would make subsequent steps easier. 

#. Image > Adjust > Threshold
#. Analyze > Analyze particles

    * Size: 100-1000
    * Circularity: 0.00-5.00
    * Show: Outlines 
    * Tick :code:`Display results`
    * Adjust the :code:`Size` parameter to include or exclude the background grain 
