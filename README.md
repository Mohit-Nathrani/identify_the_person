# identify_the_person

Python Script trained to recorgine who is the person in a given image.(only for bill gates,mark zuckerberg and elon musk)

# To Use It
- For Windows
 1. Change the current directory to the cloned folder.(assuming its "c:/identify_the_person") 
    ```
    cd "c:/identify_the_person"
    ```
 2. Copy your image file to check folded.( assume its name to be "your_image.jpg" )
    ```
    python -m scripts.label_image --graph=tf_files/retrained_graph.pb --image=check/your_image.jpg
    ```
 3. You will see something like this
 bill gates 0.999982
elon musk 1.46893e-05
mark zuckerberg 3.52075e-06