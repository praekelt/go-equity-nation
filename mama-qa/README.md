# mama-qa
MAMA Javascript sandbox application for QA.

Notes:

* The config has metric firing disabled (``skip_holodeck: true``) because the
  MAMA Javascript sandbox uses a fixed kv store key to check whether metrics
  have been published that day. ``skip_holodeck`` would be more accurately
  named ``skip_metrics`` since holodeck is no longer used by it.

Conversation configuration:

* [Javascript](https://github.com/praekelt/mama-sms/)
* [Configuration](config.json)
* [Reports](reports.json)

Raw URLs:

* Javascript (go-app-default.js): [Raw](https://raw.githubusercontent.com/praekelt/mama-sms/develop/go-app-default.js)
* Configuration: [Raw](https://raw.githubusercontent.com/praekelt/go-equity-nation/develop/mama-qa/config.json)
* Reports: [Raw](https://raw.githubusercontent.com/praekelt/go-equity-nation/develop/mama-qa/reports.json)