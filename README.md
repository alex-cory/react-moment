# react-moment
React component wrapper for moment.js

```javascript
...
import Moment from 'react-moment'
...
  render () {
    var date = new Date()
    return (
      <div>
        <Moment date={date} format={['in format', 'out format']} />
        <Moment date={date} fromNow />
        <Moment date={[date, 'format']} format={'format'} />
      </div>
    )
  }
```
