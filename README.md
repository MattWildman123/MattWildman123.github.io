<!DOCTYPE html> 
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embedded PowerPoint with Auto Refresh</title>

    <!-- JavaScript to refresh the iframe every 5 minutes -->
    <script type="text/javascript">
        function autoRefresh() {
            document.getElementById('pptFrame').src += '';
        }
        // Refresh every 300000 milliseconds (5 minutes)
        setInterval(autoRefresh, 300000);
    </script>
</head>
<body>

    <!-- Embed PowerPoint document using an iframe -->
    <iframe id="pptFrame" src=https://aaltohaps-my.sharepoint.com/personal/matt_wildman_aaltohaps_com/_layouts/15/Doc.aspx?sourcedoc={e4a3212a-b182-435f-9ba4-74abc4622425}&amp;action=embedview&amp;wdAr=1.7777777777777777&amp;wdEaaCheck=1"
        width="100%" height="700" frameborder="0" scrolling="no"></iframe>

</body>
</html>
