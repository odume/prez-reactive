## Peeking into sequences

* execute on emissions : ```myFlux.doOnNext(exec)```
* execute on completion : ```myFlux.doOnComplete(exec)```
* execute on success (Mono): ```myMono.doOnSuccess(exec)```
* execute on error termination : ```myFlux.doOnError(exec)```
* execute on subscription : ```myFlux.doOnSubscribe(exec)```