~~~markdown
```python
    #!/usr/bin/env python3
    print("Hello, World!");
    ```
~~~



```javascript
 errMess: null,

  dishes:[]}, action) => {

  switch (action.type) {

​    case ActionTypes.ADD_DISHES:

    case ActionTypes.DISHES_LOADING:

     return {...state, isLoading: true, errMess: null, dishes: []}



    case ActionTypes.DISHES_FAILED:

      return {...state, isLoading: false, errMess: action.payload};



    default:

      return state;

  }

}
```



  errMess: null,

  dishes:[]}, action) => {

  switch (action.type) {

​    case ActionTypes.ADD_DISHES:

​      return {...state, isLoading: false, errMess: null, dishes: action.payload};



​    case ActionTypes.DISHES_LOADING:

​      return {...state, isLoading: true, errMess: null, dishes: []}



​    case ActionTypes.DISHES_FAILED:

​      return {...state, isLoading: false, errMess: action.payload};



​    default:

​      return state;

  }

};```

~~~markdown
```python
    #!/usr/bin/env python3
    print("Hello, World!");
   ```
~~~

```python
print('Hello World')
```

`javascript`

