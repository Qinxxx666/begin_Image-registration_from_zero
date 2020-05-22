
Object recognition dataset
==========================

What: all model images and test images of the dataset used in paper

Vittorio Ferrari, Tinne Tuytelaars and Luc Van Gool,
Simultaneous Object Recognition and Segmentation by Image Exploration,
ECCV 2004

Why: - allow researchers to experiment with other algorithms
       and compare results

     - enabling complete visual inspection of the dataset helps to
       better appreciate scale/viewpoint changes between model views and
       test images



Contents:

models/     all models views for the 9 objects in the dataset.
            Blonde, Guard, Kellogs, Michelle: 1 model view each
            Ovo, Xmas: 6 model views each
            Car, Leo, Suchard: 8 model views each

test/       all 23 test images, for a total of 43 instances of the model
            objects (each test image contains 1 to 3 objects, 'All' contains 8 objects)
            All: all objects but Guard
            MichelleBent[A,B,C,D]: Michelle
            CarXmas[A,B]: Car, Xmas
            CarBooks: Car
            CarGlas: Car
            CarViewpoint: Car
            GuardOnBlonde: Guard, Blonde, Xmas
            GuardOnMichelle: Guard, Michelle, Leo
            KellogsClutter: Kellogs
            Kitchen[A,B]: Suchard
            LeoSleeps: Leo
            LeoHidden: Leo
            Magazines: Michelle, Blonde
            OvoLeoSuchard[A,B,C]: Ovo, Leo, Suchard
            Table[A,B]: Xmas

Contact: if you have any question do not hesitate to contact me:
         ferrari@vision.ee.ethz.ch
         I am also glad to receive news about experiments performed on this dataset.

