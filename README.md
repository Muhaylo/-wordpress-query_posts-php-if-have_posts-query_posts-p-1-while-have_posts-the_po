# -wordpress-query_posts-php-if-have_posts-query_posts-p-1-while-have_posts-the_po
 wordpress query_posts
 &lt;?php if ( have_posts() ) :
 query_posts('p=1'); while (have_posts()) : the_post(); ?> 
 &lt;?php the_title(); ?> &lt;?php the_content(); ?> 
 &lt;?php the_post_thumbnail(array(100, 100)); ?> 
 &lt;? endwhile; endif; wp_reset_query(); ?>
