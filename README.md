# Kenn's Standard Comment with ICONS

### const functions
```sh
const getInitialActive = () => {
    const tab = match.params ? match.params.tab : undefined
    if (!tab) return 0

    const view = views.find(el => el.pathname === tab)
    if (!view) return 0

    return view.id
} // 🛑
```

### components
```sh
// 🎲 🎲 🎲
const Component = props => {

  return (
    <>Hello World</>
  )
} // 🎲 🎲 🎲
```

### catch error
```
try {
    await dynamoDb.query(params).promise()
} catch(err) {
    console.log('🔥 Failed to retrieve data', err)
}
```

### notes
```
// 📝 The string true happens in local only
let folder = (week4Enable === "true" || week4Enable) ? '4weeks' : '6weeks'
```

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

License
----

MIT Since 2020
