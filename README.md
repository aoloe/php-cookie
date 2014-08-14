# Aoloe\Cookie

Read and write cookies


## Usage

    <?php
    $cookie = new Aoloe\Cookie();

    $cookie->set('test', 'yes');
    if ($cookie->is('test')) {
        $test = $cookie->get('test');
    }
    $cookie->delete('test');

    $cookie->factory()->set('test', 1);
