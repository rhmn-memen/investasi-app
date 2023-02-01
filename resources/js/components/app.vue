<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <br>
                <div class="card">
                    <div class="card-header">Form Investasi</div>

                    <div class="card-body">
                        <form action="/action_page.php">
                            <div class="form-group">
                              <label for="email">Email address:</label>
                              <input type="email" class="form-control" id="email">
                            </div>
                            <div class="form-group">
                              <label for="pwd">Password:</label>
                              <input type="password" class="form-control" id="pwd">
                            </div>
                            <div class="checkbox">
                              <label><input type="checkbox"> Remember me</label>
                            </div>
                            <button type="submit" class="btn btn-default">Submit</button>
                          </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
