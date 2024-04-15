<!DOCTYPE html>
<html>
<head>
    <title>Image Generator</title>
</head>
<body>
    <h1>Image Generator</h1>
    
    <!-- Form for user input -->
    <form id="imageForm">
        <label for="inputText">What would you like me to create:</label><br>
        <input type="text" id="inputText" name="inputText"><br><br>
        <input type="submit" value="Generate Image">
    </form>

    <!-- Div to display the generated image -->
    <div id="imageContainer">
        <p>No image generated yet.</p>
    </div>

    <!-- Script to handle form submission and API request -->
    <script>
        document.getElementById("imageForm").addEventListener("submit", function(event) {
            event.preventDefault();  // Prevent form from submitting the traditional way

            // Get the user's input
            const userInput = document.getElementById("inputText").value;

            // Define the API URL and headers
            const API_URL = "https://api-inference.huggingface.co/models/ehristoforu/dalle-3-xl-v2";
            const headers = {
                "Authorization": "Bearer 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",
                "Content-Type": "application/json"
            };

            // Define the payload with the user's input
            const payload = {
                inputs: userInput
            };

            // Send the POST request to the API
            fetch(API_URL, {
                method: "POST",
                headers: headers,
                body: JSON.stringify(payload)
            })
            .then(response => response.blob())
            .then(imageBlob => {
                // Create a URL for the image blob
                const imageUrl = URL.createObjectURL(imageBlob);

                // Create an img element to display the image
                const imgElement = document.createElement("img");
                imgElement.src = imageUrl;

                // Replace the contents of the image container with the new img element
                const imageContainer = document.getElementById("imageContainer");
                imageContainer.innerHTML = "";  // Clear previous content
                imageContainer.appendChild(imgElement);
            })
            .catch(error => {
                console.error("Error generating image:", error);
            });
        });
    </script>
</body>
</html>
