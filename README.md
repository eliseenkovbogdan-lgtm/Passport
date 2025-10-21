const change = document.getElementById("change")

function change_all(){
    if (document.getElementsByTagName('div')[3].innerText==='Ivanov'){
        document.body.style.backgroundImage = "url('passpotr_shablon.png')";
        document.getElementsByTagName('div')[3].innerText='Иванов';
        document.getElementsByTagName('div')[4].innerText='Иван';
        document.getElementsByTagName('div')[5].innerText='Иванович';
        document.getElementsByTagName('div')[6].innerText='муж';
        document.getElementsByTagName('div')[5].innerText='Москва';
    }
    else{

        if (document.getElementsByTagName('div')[3].innerText==='Иванов'){
            document.body.style.backgroundImage = "url('eng_pas.jpg')";
            document.getElementsByTagName('div')[3].innerText='Ivanov';
            document.getElementsByTagName('div')[4].innerText='Ivan';
            document.getElementsByTagName('div')[5].innerText='Ivanovich';
            document.getElementsByTagName('div')[6].innerText='male';
            document.getElementsByTagName('div')[5].innerText='Moscow';
            document.getElementsByTagName('div')[5].style.marginLeft='200px';
            document.getElementsByTagName('div')[3].style.marginTop='200px';



        }
    }
}

change.addEventListener("click", change_all)
