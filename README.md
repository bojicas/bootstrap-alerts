Bootstrap Alerts
================

Displays application bubble alerts (Growl style). Depends on <code>twbs:bootstrap</code> package.

Install
-------

```
meteor add bojicas:bootstrap-alerts
```

Usage
-----

1. Add <code>{{&gt; BootstrapAlerts}}</code> to your template / layout.
2. Call alerts with <code>Alerts.set('content', 'type')</code>, where <code>type</code> can take following values:
  * <code>success</code>
  * <code>info</code>
  * <code>warning</code>
  * <code>danger</code>

Note that you can call <code>Alerts.set('content');</code> (without a second parameter) in order to get an alert of <code>danger</code> type.

License
-------

MIT
