# MachineLearningCoursera
Repo used for programming assignments for the Coursera Machine Learning course

## Running Octave
Octave is run using docker. Further details can be found at [Github](https://github.com/ymatsunaga/docker-octave)
### Octave on Jupiter Server 
```console
docker run --rm -p 8888:8888 -v $(pwd:/source ymatsunaga/octave
```
### Octave Shell
```console
docker run --rm -p 8888:8888 -v $(pwd):/home/jovyan/work ymatsunaga/octave
```

