# Qbservable.Window Method

Include Protected Members  
Include Inherited Members

Projects each element of a queryable observable sequence.

This member is overloaded. For complete information about this member, including syntax, usage, and examples, click a name in the overload list.

## Overload List

NameDescription![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.int32)(v=VS.103))Projects each element of a queryable observable sequence into consecutive non-overlapping windows which are produced based on element count information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource, TWindowClosing>(IQbservable<TSource>, Expression<Func<IObservable<TWindowClosing>>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%602(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.linq.expressions.expression%7bsystem.func%7bsystem.iobservable%7b%60%601%7d%7d%7d)(v=VS.103))Projects each element of a queryable observable sequence into consecutive non-overlapping windows.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan)(v=VS.103))Projects each element of a queryable observable sequence into consecutive non-overlapping windows which are produced based on timing information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, Int32, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.int32%2csystem.int32)(v=VS.103))Projects each element of a queryable observable sequence into zero or more windows which are produced based on element count information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource, TWindowOpening, TWindowClosing>(IQbservable<TSource>, IObservable<TWindowOpening>, Expression<Func<TWindowOpening, IObservable<TWindowClosing>>>)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%603(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.iobservable%7b%60%601%7d%2csystem.linq.expressions.expression%7bsystem.func%7b%60%601%2csystem.iobservable%7b%60%602%7d%7d%7d)(v=VS.103))Projects each element of a queryable observable sequence into zero or more windows.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, TimeSpan, Int32)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan%2csystem.int32)(v=VS.103))Projects each element of a queryable observable sequence into a window that is completed when either it’s full or a given amount of time has elapsed.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Projects each element of a queryable observable sequence into consecutive non-overlapping windows which are produced based on timing information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, TimeSpan, TimeSpan)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan%2csystem.timespan)(v=VS.103))Projects each element of a queryable observable sequence into zero or more windows which are produced based on timing information.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, TimeSpan, Int32, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan%2csystem.int32%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Projects each element of a queryable observable sequence into a window that is completed when either it’s full or a given amount of time has elapsed.![Public method](https://reactiveui.net/assets/img/Hh303103.pubmethod(en-us,VS.103).gif "Public method")![Static member](https://reactiveui.net/assets/img/Hh244319.static(en-us,VS.103).gif "Static member")[Window<TSource>(IQbservable<TSource>, TimeSpan, TimeSpan, IScheduler)](https://msdn.microsoft.com/en-us/library/m:system.reactive.linq.qbservable.window%60%601(system.reactive.linq.iqbservable%7b%60%600%7d%2csystem.timespan%2csystem.timespan%2csystem.reactive.concurrency.ischeduler)(v=VS.103))Projects each element of a queryable observable sequence into zero or more windows which are produced based on timing information.Top

## See Also

#### Reference

[Qbservable Class](Qbservable\Qbservable.md)

[System.Reactive.Linq Namespace](System.Reactive.Linq\System.Reactive.Linq.md)