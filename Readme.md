Homework2 - Multi-class Weather Classification
2 punti

Luca Iocchi
25 nov 2019 (Ultima modifica: 10 dic 2019)
Data sets are available in
https://drive.google.com/drive/folders/1UzH28Q8xki8_DMYdDgHxi40-CJ800Kaq

Read the README file in this folder for further instructions about data.

Project development

1) Solve the image classification problem in two modes: A) define a CNN and train it from scratch, B) apply transfer learning and fine tuning from a pre-trained model.
For training you can use any subset of the MWI dataset.
2) Evaluate the two models in a proper way. Discuss the best model and motivate the choice. Testing can be done either with cross-validation on MWI or with the SMART-I weather test set.
3) Write a report (about 10 pages) explaining all the work done: design and implementation choices, evaluation procedure and results. Reports must be individual.
4) Submit a set of images to be used to define a new test set
5) Submit your best model (layout and weights)

IMPORTANT: when submitting new images for the new test set take care of copyright and privacy. Submit only images taken by yourself (not downloaded from web) and without faces or other personal information of any kind. By submitting these images, you also give permission to be used for non-commercial research and educational purposes and possibly to be added in the MWI dataset.

Submission procedure

Submit through classroom (e-mail submissions will not be accepted) the following files
separately (not inside a ZIP file). Use file names as shown below, replace matricola with your matricola code.
1) matricola.PDF file of the report (no other formats accepted, not included in a ZIP file),
2) matricola_code.ZIP file with the code (without data set),
3) matricola_images.ZIP file with new images subdivided in folders named exactly: HAZE, RAINY, SNOWY, SUNNY. 10 to 20 images possibly balanced, but it is not necessary to fill all the classes.
4) matricola.h5 file containing the best model to be evaluated with the test set (more details are in the README file of the shared folder).
5) matricola.csv Your evaluation on the blind test set (more details are in the README file of the shared folder).

Example: if your matricola is 1234567, you should submit 5 files with names: 1234567.pdf, 1234567_code.zip, 1234567_images.zip, 1234567.h5, 1234567.csv

Deadline: 15/12/2019 11:59 PM CET

NOTES:
1) for exam bonus, only the PDF report (and possibly the code) will be considered. Contribution to the new test set and evaluation of best models (still mandatory) will be performed only for educational purposes.
2) if you use Keras, save the model as shown in ML Exercise 10. If you use other libraries, save the model using tools available for that library.
3) blind test set and instructions for evaluation are described in the README file in the shared folder.
