## Information

<table>
<tr> 
<td>Package</td><td>gulp-coffee-react</td>
</tr>
<tr>
<td>Description</td>
<td>Compiles CoffeeScript & React</td>
</tr>
<tr>
<td>Node Version</td>
<td>>= 0.9</td>
</tr>
</table>

## Usage

```javascript
var coffeex = require('gulp-coffee-react');

gulp.task('coffeex', function() {
  gulp.src('./src/*.coffee')
    .pipe(coffeex({bare: true}).on('error', gutil.log))
    .pipe(gulp.dest('./public/'))
});
```
