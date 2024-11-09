## change the directory:
    cd /etc

## confirm current location:
    pwd

## to get list in a specific location:
    ls /etc -la

## getting help for anything new:
    aircrack-ng --help

## Detaild information about the library you want to use, Example:
    man aircrack-ng

## Finding stuff with LOCATE:
    locate aircrack-ng

## Finding Binaries with WHEREIS:
    whereis aircrack-ng

## Finding Binaries in PATH Variables with WHICH:
    which aircrack.ng

## Performing more powerful searches with find:
    find /(1) -type f(2) -name apache2(3)

    Explanation:
        (1): state the dir from which to start search
        (2): which type of file to search
        (3): giving the name of the file to search

## Using FIND with all extention by adding .* :
    find /etc -type f -name apache2.*

## Checkign how many process is running currently in your PC:
    ps aux

## If you want to see a specific application running or not, in our instance apache2:
    ps aux | grep apache2