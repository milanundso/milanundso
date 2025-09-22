# <div align="center">Hi, I'm Milan 🗻 </div>

```java
public class Milan extends GitHubProfile {

    private boolean knowsJava;
    private boolean justPressingKeys;
    private boolean deservesAFollow;

    @Override
    public void onRun() {
        this.knowsJava = false;
        this.justPressingKeys = true;
        this.deservesAFollow = true;

        if (!knowsJava && justPressingKeys) {
            System.out.println("I have no idea what I'm doing");
        } else {
            System.out.println("Something in the code changed, I still don't know what I'm doing");
        }

        if (deservesAFollow) {
            System.out.println("You should follow me");
        } else {
            System.out.println("No problem duh");
        }
    }

}

```
