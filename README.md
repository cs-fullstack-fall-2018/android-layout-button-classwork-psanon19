# Classwork - Create a constrained layout with simple widget interaction

* Create a simple button click counter application
* Reference included blueprint image for specifications
* Use the following code snippet to work with your layout

```
        userInput = (EditText) findViewById(R.id.editText);
        button = (Button) findViewById(R.id.button);
        textView = (TextView) findViewById(R.id.textView);
        View.OnClickListener ourOnClickListener = new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                numTimesClicked = numTimesClicked + 1;
                String result = "\nClicked " + numTimesClicked + " times";
                textView.append(result);

            }
        };
        button.setOnClickListener(ourOnClickListener);
        ```
