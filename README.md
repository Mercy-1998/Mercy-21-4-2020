#Mercy-22-4-2020

done.. upto creating.. overlayout.. like creating cards. wthout adding function.Done that much today.I will share the screenshot




# Mercy-21-4-2020

import React, { useState, useEffect } from 'react'

function HookCounterOne() {

    const [ count, setCount ] = useState(0)
    const [ name, setName ] = useState('')

    useEffect(() => {
        console.log('useEffect - Updating document title')
        document.title = `You clicked ${count} times`
    }, [count])

    return (
        <div>
            <input type='text' value={name} onChange={e => setName(e.target.value)} />
           <button onClick={() => setCount(count + 1)}>Click {count} times</button> 
        </div>
    )
}

export default HookCounterOne


Hii saswati.. 
        Today i learned this.. useEffect- conditionally run effects.Then after knowing the task i searched and collected details about trello.Like material-ui.. etc.. i collected.

