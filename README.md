# CMB2 Conditionals Work With Nested Group and Can use directly in Plugin and Theme

## Installation

If installing the plugin from wordpress.org:

1. Upload cmb2-conditionals.php file into plugin directory of your CMB2 Directory
2. Create Admin Directory in CMB2 Plugin Directory
3. Upload cmb2-conditionals.js file into Admin Directory
4. Done

## HOW to USE

1. Open your meta box file.
2. Include cmb2-conditionals.php file on top.

```
if ( file_exists( dirname( __FILE__ ) . '/cmb2/plugins/cmb2-conditionals.php' ) ) {
	require_once dirname( __FILE__ ) . '/cmb2/plugins/cmb2-conditionals.php';
	cmb2_conditionals_init();
}
```

3. Use Attribute to show / Hide Group Box based on Parent Group Field Value
