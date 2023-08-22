Summary

-Each component has its own template: 

@Component({ selector: 'app', template:
`<h1>{{title}}</h1`})

-There are three types of data binding 

-We can intersect the lifecycle of a component :

ngOnInit() { this.data = // Retrieve data }

-Components can interact with each other:

@Output() fromChild = new EventEmitter<boolen>();
