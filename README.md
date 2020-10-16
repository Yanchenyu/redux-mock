## mock redux源码

dispatch(action(data));


action:

export const action = (data) => ({
    type: 'ACTION_TYPE',
    data
})

reducer: 

export const reducer = (type, initialstate) => {
    switch(type) {
        case 'ACTION_TYPE':
            return newState
    }
}

store:

const store = createStore(
    reducer
)

