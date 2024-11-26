<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <!-- Bootstrap CSS -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

    <div class="container my-5">
        <!-- Header -->
        <header class="text-center">
            <h1 class="display-4">About Me</h1>
            <p class="lead">Welcome to my personal webpage!</p>
        </header>

        <!-- Navigation Buttons -->
        <div class="text-center my-4">
            <a href="#about" class="btn btn-primary mx-2">About</a>
            <a href="#contact" class="btn btn-secondary mx-2">Contact</a>
        </div>

        <!-- Profile Image -->
        <div class="text-center">
            <img src="Lima.jpeg" class="rounded-circle img-thumbnail img-fluid" alt="Profile Image"
                style="width: 250px; height: 250px;">
        </div>


        <!-- About Section -->
        <section id="about" class="my-5">
            <h2>About Me</h2>
            <p>Hello! My name is Lima Faizi, and I am a student at American University of Afghanistan. I enjoy learning
                new things and
                am passionate about AI development.</p>
        </section>

        <!-- Table Section -->
        <section class="my-5">
            <h3>Skills and Interests</h3>
            <table class="table table-bordered">
                <thead class="thead-dark">
                    <tr>
                        <th>Skill</th>
                        <th>Proficiency</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>AI Development</td>
                        <td>Intermediate</td>
                    </tr>
                    <tr>
                        <td>Graphic Design</td>
                        <td>Advanced</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Preferences (Radio Buttons/Checkboxes) -->
        <section class="my-5">
            <h4>Preferences</h4>
            <form>
                <p>Favorite Activity:</p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="activity" id="reading" value="reading">
                    <label class="form-check-label" for="reading">Reading</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="activity" id="sports" value="sports">
                    <label class="form-check-label" for="sports">Sports</label>
                </div>

                <p class="mt-3">Hobbies:</p>
                <div class="form-check">
                    <input class="form-check-input" type="checkbox" id="coding" value="coding">
                    <label class="form-check-label" for="coding">Coding</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="checkbox" id="traveling" value="traveling">
                    <label class="form-check-label" for="traveling">Traveling</label>
                </div>
            </form>
        </section>
    </div>

    <!-- Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>
