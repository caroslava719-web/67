document.addEventListener('DOMContentLoaded', function() {
    const form = document.getElementById('orderForm');
    if (form) {
        form.addEventListener('submit', function(event) {
            event.preventDefault();
            const name = document.getElementById('username').value;
            alert('Спасибо, ' + name + '! Ваша заявка успешно отправлена. Мы свяжемся с вами в ближайшее время.');
            form.reset();
        });
    }
});
