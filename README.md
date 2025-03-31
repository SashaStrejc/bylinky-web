# bylinky-web<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bylinkový kalendář</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        table { width: 100%; border-collapse: collapse; }
        th, td { border: 1px solid #ddd; padding: 8px; text-align: left; }
        th { background-color: #4CAF50; color: white; }
        .category { font-weight: bold; }
        .search-bar { margin-bottom: 10px; }
    </style>
</head>
<body>
    <h1>Bylinkový kalendář</h1>
    <input class="search-bar" type="text" id="search" onkeyup="filterTable()" placeholder="Hledat bylinku...">
    <table id="herbTable">
        <thead>
            <tr>
                <th>Bylinka</th>
                <th>Kategorie</th>
                <th>Období sběru</th>
                <th>Využití</th>
            </tr>
        </thead>
        <tbody>
            <tr><td>Kopřiva</td><td>Vlasy, Čaj</td><td>Bře - Zář</td><td>Podporuje růst vlasů, detoxikace</td></tr>
            <tr><td>Bříza</td><td>Vlasy</td><td>Dub - Kvě</td><td>Regenerace vlasů, pročištění organismu</td></tr>
            <tr><td>Přeslička</td><td>Vlasy</td><td>Čvn - Srp</td><td>Posiluje vlasy a nehty</td></tr>
            <tr><td>Lípa</td><td>Rýma/Kašel, Čaj</td><
