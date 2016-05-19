[redux-immutablejs](https://github.com/indexiatech/redux-immutablejs) modify.

```
createReducer(initialState, {
    [TYPES.OPEN_MENU]: (menu, action)=> {
        return menu.mergeDeep({
            show: true
        });
    },

    [TYPES.CLOSE_MENU]: (menu, action)=> {
        return menu.mergeDeep({
            show: false
        });
    }
}, function alltype(menu, action){
 //...
});
```
