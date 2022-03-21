<script src="steinbmarcsi.github.io/familytree.js"></script>
<div style="width:100%; height:700px;" id="tree"/>

    <script>
        var family = new FamilyTree(document.getElementById("tree"), {
            nodeBinding: {
                field_0: "name"
            },
            nodes: [
                { id: 1, pids: [2], name: "Amber McKenzie" },
                { id: 2, pids: [1], name: "Ava Field" },
                { id: 3, mid: 1, fid: 2, name: "Peter Stevens" }  
            ]
        });
    </script> 
