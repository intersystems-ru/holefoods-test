# holefoods-test
Test repo with HoleFoods classes and dfi files to test UDL import/export

Can be imported with:

#1 [cache-udl](https://github.com/intersystems-ru/cache-udl)
1. install cs.alles
2. Download the code from holefoods-test to the "Path"
3. Import the code and DeepSee staff
```
// set the workdir
d ##class(sc.alles).workdir("Path")
// import all the classes, pivots and dashes
d ##class(sc.alles).import()
```

#2 [CacheUpdater](https://github.com/intersystems-ru/CacheUpdater)
1. Import CacheUpdater package
2. Import the code and DeepSee staff:
```
// run in the terminal
d ##class(CacheUpdater.Task).Update("intersystems-ru","holefoods-test","")
