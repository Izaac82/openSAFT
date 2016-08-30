# openSAFT
An open implementation of the Synthetic Aperture Focusing Technique (SAFT). 
This code was created initially for ultrasonic concrete inspection. The purpose
behind releasing the code is to promote discussion and open exploration of the 
SAFT method for concrete non-destructive inspection. 
 
Files: 

   [OpenSAFT_QuickGUIInstaller.exe](https://github.com/Jabittner/openSAFT/blob/master/OpenSAFT_QuickGUIInstaller.exe) - Quick Graphical Program to Demonstrate Reconstruction Options

   main.m - General Starter File To Inspect Example Dataset (JAB4.lbv)

   qgui.m - Example GUI built using MATLAB to Test Different Color Gains

   a_filereader.m - Simple binary file reader configured to read in 66 time domain signals 2048 points in length. 

   a_plotBscan.m - SAFT Algorithm to assemble a B-Scan estimate and plot as a image


# Submissions
-This is an open project, the authors welcome suggestions, new code, and posting of problem datasets. 

-Q.C. is missing from this processing method completely. Please feel free to submit code for Q.C. Algorithms. 


# Disclaimer 
This code was written based upon existing literature, and some creative problem solving to speed up the process. 
The enclosed code is for research and education purposes. The author does not claim any accuracy 
of the methods used. If you find an error, or poor assumption please fix it and send in your code. 

# References

Clayton, D., Smith, C., Ferraro, C., Nelson, J., Khazanovich, L., Hoegh, K., … Ham, S. (2013). Evaluation of Ultrasonic Techniques on Concrete Structures. Report: ORNL/TM-2013/430. Oak Ridge, TN: Oak Ridge National Laboratory. 

Jensen, J. A., Nikolov, S. I., Gammelmark, K. L., & Pedersen, M. H. (2006). Synthetic aperture ultrasound imaging. Ultrasonics, 44 Suppl 1, e5–15. doi:10.1016/j.ultras.2006.07.017

Langenberg, K.-J., Marklein, R., & Mayer, K. (2012). Ultrasonic Nondestructive Testing of Materials: Theoretical Foundations. Boca Raton, FL: CRC Press.

Maierhofer, C., Reinhardt, H.-W., & Dobmann, G. (2010). Non-destructive Evaluation of Reinforced Concrete Structures: Volume 2 Non-destructive Testing Methods. Boca Raton, FL: CRC Press.

Shokouhi, P., Wostmann, J., Schneider, G., Milmann, B., Taffe, A., & Wiggenhauser, H. (2011). Nondestructive Detection of Delamination in Concrete Slabs: A Multi-Method Investigation In Transportation Research Record 2011 Annual Meeting (Vol. 3). 

Yao, H. (1997). Synthetic Aperture Methods for Medical Ultrasonic Imaging. Undefined Thesis in Computer Science. University of Oslo. Retrieved from http://ftp.project.ifi.uio.no/publications/cand-scient-theses/HYao.pdf
