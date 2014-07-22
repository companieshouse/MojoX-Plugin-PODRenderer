# NAME

MojoX::Plugin::PODRenderer

# SYNOPSIS

    use MojoX::Plugin::PODRenderer;

    $self->plugin( 'MojoX::Plugin::PODRenderer' );

# DESCRIPTION

Perl pod rendering plugin. Based on the original Mojo::PODRenderer.

# METHODS

## \[void\] register( $app, $conf )

Called by Mojo app to register the plugin

    @param  app     [mojo application]  ref to the mojo application
    @param  conf    [hash]              configuration hash
