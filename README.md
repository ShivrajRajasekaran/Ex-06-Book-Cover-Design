<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Your CSS styles here */
    </style>
    <title>Book Cover Page</title>
</head>
<body>
    <div class="bookpage">
        <!-- Your HTML content here -->
    </div>

    <script>
        // JavaScript code to filter elements by class name
        document.addEventListener("DOMContentLoaded", function() {
            // Get all elements with class name "insight"
            var insightElements = document.getElementsByClassName("insight");

            // Loop through the elements and apply a filter
            for (var i = 0; i < insightElements.length; i++) {
                var element = insightElements[i];

                // Check if you want to keep or hide the element based on a condition
                // For example, you can hide elements with a specific color
                if (element.style.color === "brown") {
                    // You can modify the element's style, hide it, or do any other manipulation
                    element.style.display = "none";
                }
            }
        });
    </script>
</body>
</html>
