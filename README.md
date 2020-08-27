# gravity vs layout_gravity in Android

This project demonstrates the difference between `gravity` and `layout_gravity` in Android.

The app layout has an overall `LinearLayout`.

There are two regions to the screen; the upper region occupies 50% of the screen and is composed of a `LinearLayout`, and the bottom region is the same. The property `layout_weight` is set to 1 for both `LinearLayout`s.

Finally, in the upper panel, several `TextView`s are set with `gravity` to left, right, and center. In the lower panel, the `TextView`s have their `layout_gravity` set to left, right, and center.

This demo is just used as a quick visual reminder of the difference between `gravity` and `layout_gravity`.

[Link to documentation for `layout_gravity`](https://developer.android.com/reference/android/widget/LinearLayout.LayoutParams)

[Link to documentation for `gravity`](https://developer.android.com/reference/android/view/Gravity)

[Link to StackOverflow discussion](https://stackoverflow.com/questions/3482742/what-is-the-difference-between-gravity-and-layout-gravity-in-android)

Screenshot of the demo:

![Android layout_gravity vs gravity](https://github.com/fullStackOasis/android-gravity-vs-layout_gravity/raw/master/android-demo-layout_gravity-vs-gravity.png)
