# Capacitor Firebase Remote Config Plugin

Capacitory community plugin for firebase remote config.

<!-- Badges -->
<!-- <a href="https://npmjs.com/package/@capacitor-community/http">
  <img src="https://img.shields.io/npm/v/@capacitor-community/http.svg">
</a>
<a href="https://npmjs.com/package/@capacitor-community/http">
  <img src="https://img.shields.io/npm/l/@capacitor-community/http.svg">
</a> -->

## Maintainers

| Maintainer | GitHub | Social | Sponsoring Company |
| -----------| -------| -------| -------------------|
| Priyank Patel | [priyankpat](https://github.com/priyankpat) | [N/A](https://twitter.com) | Ionic |

Mainteinance Status: Actively Maintained

## Installation

```bash
npm install @capacitor/firebase-remote-config
npx cap sync
```

On iOS, no further steps are needed.

On Android, register the plugin in your main activity:

```java
import com.getcapacitor.community.firebaserc;

public class MainActivity extends BridgeActivity {
  @Override
  public void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);

    // Initializes the Bridge
    this.init(savedInstanceState, new ArrayList<Class<? extends Plugin>>() {{
      // Additional plugins you've installed go here
      // Ex: add(TotallyAwesomePlugin.class);
      add(FirebaseRemoteConfig.class);
    }});
  }
}
```

## Configuration

No configuration required for this plugin