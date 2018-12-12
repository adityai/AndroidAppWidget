#Android Google Play Dashing Widget

[Dashing](https://github.com/Shopify/dashing) Widget for displaying current Google Play Ratings.

![Preview](https://gist.githubusercontent.com/x2on/7007757c222aacbd102b/raw/11917bf5a1ef6d3a5d21b8752d4a92bef888ceab/Preview.png)

##Usage

To use this widget, copy `google.html`, `google.coffee`, and `google.scss` into the `/widgets/google` directory. Put the `google.rb` file in your `/jobs` folder. Copy `google.yml` into your `/config` folder and set the `app_identifier`

Add `gem 'market_bot'` to your `Gemfile` and run `bundle`

To include this widget in a dashboard, add the following snippet to the dashboard layout file:

```html
<li data-row="1" data-col="1" data-sizex="1" data-sizey="1">
    <div data-id="Google" data-view="Google" data-title="Play Store"></div>
</li>
```