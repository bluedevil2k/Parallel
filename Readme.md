Parallel
=======

A utility class that replicates the Stream's parallel() functionality found in Java 8, for projects that can't upgrade to Java 8.

Example Usage
------
    Parallel.forEach(elems,
        new Parallel.Function<Integer>() {
            public void execute(Integer param) {
                System.out.println(param);
            };
        });
