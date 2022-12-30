# Tailwind Dark Mode Remover

Easily remove Dark Mode classes from your Tailwind CSS code 🌙❌ Simply paste in your code. The updated code will be generated automatically. 

# Why?

If you're not using dark classes in your design, there's no reason to keep them in your code. Every class you include in your code adds a little bit of extra weight, so removing unnecessary classes can help reduce the overall size of your stylesheets and make your website faster to load.

# How?

This tool uses a regular expression to search for and remove dark classes from your Tailwind CSS code.

```
/dark:\w+([-:\w]*\w)/g
```

You can use this regular expression to remove dark classes from your code manually, or you can use this tool to do it for you.
