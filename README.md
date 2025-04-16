# surprisebuild

To run this Rama module locally, do the following:

    ./rama devZookeeper

    ./rama conductor

    ./rama supervisor

    rama deploy --action launch jar --jar target/building-with-rama-clj-1.0.0-SNAPSHOT-standalone.jar --module nlb.family-tree/FamilyTreeModule --tasks 64 --threads 16 --workers 8 --replicationFactor 1