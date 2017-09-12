# npm-module-in--git-hub

Example use:

```
import {HelloWorld} from 'hwrld'

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
  title = 'app';

  constructor() {
    HelloWorld.sayHello();  
  }
}
```
