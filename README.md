
### logic
1. data Video clips from FRVSR datatrain.txt, clip each sequence with 10 frame.
      
     Todo: write script to create dataset
     
           step：
           
                  1.downsample each frame by 2, downsample each frame by 4.
                  
                  2. warp 10 frame as a sequence->into separate folder
                  
                  3. manually select hard negative examples.
                  
2. convert each seq into binay frames.

3. random sampling and data aug are solved in torch.dataset module

4. implement the model.
