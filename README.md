# mycodeblog
Curso de Spring Boot com Thymeleaf, Bootstrap, PostgreSQL e Spring Security mostrando o passo a passo de como construir um blog. 

Scriptspara inserir o summernote no formulário:

------------------------Scripts para incluir summernote no head HTML----------------------------------

    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/summernote/0.8.12/summernote-bs4.css" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/summernote/0.8.12/summernote-bs4.js"></script>
    
--------------------------------------------------------------------------------------------------------


--------------------------------Scripts para incluir summernote no body HTML----------------------------
<script>
    $('#summernote').summernote({
        placeholder: 'Texto *',
        tabsize: 2,
        height: 300
    });
</script>
--------------------------------------------------------------------------------------------------------
