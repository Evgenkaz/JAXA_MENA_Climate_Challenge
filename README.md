# [JAXA MENA Region Climate Change Impact Challenge](https://bitgrit.net/competition/21)

### Preprocessing


- <b>concat_df_train.ipynb</b> - Getting the final dataset from files in the vegetation_index directory and saving


### Prediction


 - <b>jaxa_solution.ipynb</b> - We get the final prediction
 - The approach is based on the following - similar months of previous years are taken
   for 9, 8 are added, and for 12, 11 more smoothing months, 3 months remained as is. 
   The average vegetation_index is calculated by coordinates and month and we make a prediction
   for the next one.This approach has proven itself better in validation than using models.

### Hardware

```shell
 Processor - intel core i9
 RAM - 64g
 OS - WINDOWS 10
```
### Leaderboard

Validation <b>0.944435</b>, Public <b>0.919311</b>, Private <b>0.919615</b>
