Summary :

-DI is a popular design pattern

-Using services in Angular is recommended :


@Component({
  providers: [ UserService ]
})


RxJS and FRP are powerful concepts

-Use the HttpClient to fetch data from an API :


this.http.get(url).retry().pipe().subscribe()




