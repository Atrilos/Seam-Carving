# Hyperskill.org - Seam Carving

My solution for the hyperskill.org problem: Seam Carving

https://hyperskill.org/projects/100

## Algorithm Description

Seam carving (or liquid rescaling) is an algorithm for content-aware image resizing,  
developed by Shai Avidan, of Mitsubishi Electric Research Laboratories (MERL), and Ariel Shamir,  
of the Interdisciplinary Center and MERL.

See more: [Wikipedia - Seam Carving](https://en.wikipedia.org/wiki/Seam_carving)

Basically, the algorithm creates a map of an image where parts of the image with fewer edges have less *energy*.  
*Less energy = Less content*  
So the algorithm removes such parts first to resize the image, and in theory, resizing  
won't reduce the quality of the image and won't cut any meaningful parts of it.

## Quick start

Use following parameters:  
`
-in <input file name> -out <output file name> -width <number of width pixels to be reduced> -height <number of height pixels to be reduced>
`
