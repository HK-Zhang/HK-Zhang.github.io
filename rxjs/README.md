# Play Rxjs6 Examples in VS Code

## Setup development environment

1. Install Visual Studio Code

    + [Visual Studio Code][vs]

2. Git Clone Source Code

    + `git clone https://github.com/HK-Zhang/Rxjs6-Example.git`

3. Install NPM package

    + `npm install`

4. Change app.ts as below to debug a particular piece of code

```ts
let rxjsMethod = "takewhile";
```

5. Ctrl + Shit + B to build the whole project

6. Press F5 to debug and check result at DEBUG CONSOLE

---
## Rxjs Example List

1. Combination
    + [combineAll](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/combineAll.md)
    + [combineLatest](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/combineLatest.md)
    + [concat](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/concat.md)
    + [forkJoin](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/forkJoin.md)
    + [merge](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/merge.md)
    + [mergeAll](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/mergeAll.md)
    + [pairwise](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/pairwise.md)
    + [race](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/race.md)
    + [startWith](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/startWith.md)
    + [withLatestFrom](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/withLatestFrom.md)
    + [zip](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Combination/zip.md)

2. Conditional
    + [defaultIfEmpty](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Conditional/defaultIfEmpty.md)
    + [every](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Conditional/every.md)
    + [iif](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Conditional/iif.md)
    
3. Creation
    + [create](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/create.md)
    + [empty](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/empty.md)
    + [from](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/from.md)
    + [from.promise](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/from.promise.md)
    + [interval](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/interval.md)    
    + [of](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/of.md)    
    + [range](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/range.md)
    + [throwError](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/throwError.md)
    + [timer](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Creation/timer.md)    

4. ErrorHandle
    + [catchError](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/ErrorHandle/catchError.md)
    + [retry](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/ErrorHandle/retry.md)
    + [retryWhen](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/ErrorHandle/retryWhen.md)
    
5. Filter
    + [debounce](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/debounce.md)
    + [debounceTime](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/debounceTime.md)
    + [distinctUntilChanged](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/distinctUntilChanged.md)
    + [filter](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/filter.md)
    + [first](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/first.md)
    + [ignoreElement](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/ignoreElement.md)
    + [last](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/last.md)
    + [sample](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/sample.md)
    + [single](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/single.md)
    + [skip](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/skip.md)
    + [skipUntil](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/skipUntil.md)
    + [skipWhile](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/skipWhile.md)
    + [take](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/take.md)
    + [takeUntil](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/takeUntil.md)
    + [takeWhile](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/takeWhile.md)
    + [throttle](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/throttle.md)
    + [throttletime](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Filter/throttletime.md)
    
6. Multicasting
    + [multicast](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Multicasting/multicast.md)
    + [publish](https://github.com/HK-Zhang/Rxjs6-Example/blob/master/Multicasting/publish.md)
    + [share](https://github.com/HK-Zhang/Rxjs6-Example/blob/Multicasting/ErrorHandle/share.md)
    + [shareReplay](https://github.com/HK-Zhang/Rxjs6-Example/blob/Multicasting/ErrorHandle/shareReplay.md)
    
[vs]: https://code.visualstudio.com
